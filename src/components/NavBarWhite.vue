<template>
  <div>
    <div class="nav-clip">
      <nav class="mobilenav bg1">
        <div class="MenuLogo">
          <g-link to="/">
            <img alt="weCare logo" src="../assets/wecarelogo.png" width="50" />
          </g-link>
        </div>
        <div class="MenuIconContainer">
          <div class="MenuIcon">
            <span></span>
            <span></span>
            <span></span>
          </div>
        </div>
        <div class="MenuLinksContainer">
          <div class="MenuLinks">
            <ul>
              <li>
                <g-link to="/About">About</g-link>
              </li>
              <li>
                <g-link to="/Events">Events</g-link>
              </li>
              <li>
                <g-link to="/Gallery">Gallery</g-link>
              </li>
              <li class="mobiledonate">
                <g-link to="/">Donate</g-link>
              </li>
              <li class="mobilevol">
                <g-link to="/">Volunteer</g-link>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
    <div class="desktop">
      <div class="nav-clip">
        <nav class="nav bg1">
          <g-link to="/">
            <img alt="weCare logo" src="../assets/wecarelogo.png" width="50" />
          </g-link>
          <g-link class="link bg1" to="/about/">About</g-link>
          <g-link class="link bg1" to="/events/">Events</g-link>
          <g-link class="link bg1" to="/gallery/">Gallery</g-link>
          <g-link class="link donate bg1" to="/">Donate</g-link>
          <g-link class="link volunteer bg1" to="/">Volunteer</g-link>
        </nav>
      </div>
    </div>
  </div>
</template>

<script>
import Vue100vh from "vue-div-100vh";
export default {
  name: "NavWhite",
  components: {
    Vue100vh,
  },
  mounted() {
    const btnHamburger = document.querySelector(".MenuIcon");
    const menuIcon = document.querySelector(".MenuIconContainer");
    const body = document.body;
    const overlay = document.querySelector(".MBLinksContainer");
    const menu = document.querySelector(".MenuLinksContainer");

    btnHamburger.addEventListener("click", function() {
      console.log("click hamburger");
      btnHamburger.classList.toggle("open");
      overlay.classList.toggle("inactive");

      if (btnHamburger.classList.contains("open")) {
        document.body.classList.add("no-scroll");
        // menu.style.transform = "translateX(0)";
      } else {
        document.body.classList.remove("no-scroll");
        //  menu.style.transform = "translateX(-100%)";
      }
    });
  },
};
</script>

<style lang="scss" scoped>
.no-scroll {
  overflow: hidden;
}
.bg1 {
  background: white;
  color: #a5a5a5;
}
.bg2 {
  background: #c41c48;
  color: white;
}

.nav-clip {
  position: relative;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  clip: rect(auto, auto, auto, auto);
  -webkit-clip: rect(auto, auto, auto, auto);
  pointer-events: none;
}
.mobilenav {
  display: none;
  @media (max-width: 750px) {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    padding: 15px 30px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    pointer-events: painted;
    z-index: 20;
    transform: perspective(0);
  }
}
.MenuLogo {
  z-index: 21;
}
.MenuIconContainer {
  display: flex;
  justify-content: center;
  align-items: center;

  //   .open {
  //     > span:first-child {
  //       transform: translateY(7px) rotate(45deg);
  //     }

  //     > span:nth-child(2) {
  //       transform: translateX(-20px);
  //       opacity: 0;
  //     }

  //     > span:last-child {
  //       transform: translateY(-7px) rotate(-45deg);
  //     }
  //   }
}

.MenuIcon {
  cursor: pointer;
  background: transparent;
  border: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 1.875rem;
  width: 1.25rem;
  z-index: 25;
  outline: none;

  span {
    width: 100%;
    height: 2px;
    background: #c41c48;
    border-radius: 5px;
    transition: opacity 500ms, transform 500ms;

    &:not(:first-child) {
      margin-top: 0.3125rem;
    }
  }
}

.MenuLinksContainer {
  background: white;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  display: flex;
  position: absolute;
  z-index: 10;
  top: 0;
  right: 0;
  bottom: 0;
  height: 100vh;
  width: 100%;
  transform: translateX(-100%);
  transition: 0.8s cubic-bezier(0.2, 0.8, 0.2, 1);
}
.MenuLinks {
  position: absolute;
  /*bottom: calc(200px - 10%);*/
  text-align: left;
  left: 30px;

  ul {
    width: 100%;
    padding: 0;
    li {
      list-style: none;
      &:not(:first-child) {
        margin-top: 25px;
      }
      a {
        text-decoration: none;
        color: black;
        font-size: 25px;
        font-weight: 600;
        letter-spacing: -1.5px;
      }
    }
    .mobiledonate {
      a {
        color: #c41c48;
      }
    }
    .mobilevol {
      a {
        color: #c41c48;
      }
    }
  }
}

.desktop {
  display: block;

  @media (max-width: 750px) {
    display: none;
  }
  a {
    &:not(:first-child) {
      font-size: 16px;
      font-weight: 400;
      background-color: rgba(255, 255, 255, 1);
      padding: 8px;
      border-radius: 5px;
      transition: all 500ms cubic-bezier(0.2, 0.8, 0.2, 1);

      &:hover {
        background-color: rgb(255, 209, 224);
        color: #c41c48;
      }
    }
  }
  .donate {
    color: #c41c48;
  }
  .volunteer {
    color: #c41c48;
  }
}
.nav {
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
  right: 0;
  margin: 0 auto;
  padding: 10px 0%;
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  pointer-events: painted;
  z-index: 20;
}
</style>
