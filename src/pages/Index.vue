<template>
  <Layout>
    <div class="MBLinksContainer inactive">
      <div class="MBLogo">
        <g-link to="/">
          <img alt="weCare logo" src="../assets/wecarelogo.png" width="50" />
        </g-link>
      </div>
      <div class="MBIconContainer">
        <div class="MBIcon">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>
      <div class="MBLinks">
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
    <div class="MBLinksContainerRed inactive">
      <div class="MBLogoRed">
        <g-link to="/">
          <img
            alt="weCare logo"
            src="../assets/wecarelogowhite.png"
            width="50"
          />
        </g-link>
      </div>
      <div class="MBIconContainerRed">
        <div class="MBIconRed">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>
      <div class="MBLinksRed">
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
    <div class="MBLinksContainerRed2 inactive">
      <div class="MBLogoRed2">
        <g-link to="/">
          <img
            alt="weCare logo"
            src="../assets/wecarelogowhite.png"
            width="50"
          />
        </g-link>
      </div>
      <div class="MBIconContainerRed2">
        <div class="MBIconRed2">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>
      <div class="MBLinksRed2">
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
    <div>
      <div class="header">
        <h1>Contribute your quota in making the world a better place.</h1>
        <h4>
          Use your time to serve the world and you'll find that it serves you.
        </h4>
        <g-link class="volunteers" to="/">Become a Volunteer</g-link>
      </div>
      <NavWhite />
    </div>
    <div>
      <div class="section2">
        <img class="l2l" src="../assets/livetolove1.png" />
        <div class="section2text">
          <h2>Every year, we Live to Love!</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime vero
            impedit rem. Inventore, odio odit! Enim exercitationem repellendus
            deleniti corrupti vitae quo aliquid ipsam. Consectetur similique
            corrupti obcaecati dolor nostrum?
          </p>
        </div>
        <NavRed />
      </div>
    </div>
    <div>
      <div class="section3">
        <div class="section3title">
          <h1>Help us make our next outreach a successful reality</h1>
        </div>
        <div class="event">
          <div class="events">
            <div class="escontainer">
              <div class="eventscroll"></div>
            </div>
            <div class="event1">
              <img src="../assets/image1.png" />
              <h3>Live To Love Maiden Edition</h3>
              <p class=" p1 fade-in">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Tempora non maxime ex, eveniet ipsa molestiae ea.
              </p>
            </div>
            <div class="event2">
              <img src="../assets/image1.png" width="650" />
              <h3>Live To Love 2.0</h3>
              <p class="p2">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Reprehenderit expedita necessitatibus cupiditate aspernatur
                quasi animi laboriosam odio.
              </p>
            </div>
            <div class="event3">
              <img src="../assets/image1.png" width="650" />
              <h3>Live To Love 3.0</h3>
              <p class="p3">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Explicabo deserunt quam inventore deleniti quod blanditiis.
              </p>
            </div>
          </div>
          <div class="images">
            <img src="../assets/image1.png" />
            <img src="../assets/image1.png" />
            <img src="../assets/image1.png" />
          </div>
        </div>
        <div class="line"></div>
        <div class="sec3text">
          <div class="sectext">
            <h1>
              View some of the beautiful captured moments from previous
              outreaches
            </h1>
            <div class="gallerylink">
              <g-link class="gallery" to="/">View Gallery</g-link>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div>
      <div class="section4">
        <div class="sec4">
          <div class="Don">
            <h1>
              "We make a living by what we get, we make a life by what we give"
            </h1>
            <g-link to="/">Donate</g-link>
          </div>
        </div>
        <Footer />
        <NavRed2 />
      </div>
    </div>
  </Layout>
</template>

<script>
import NavWhite from "@/components/NavBarWhite.vue";
import NavRed from "@/components/NavBarRed.vue";
import NavRed2 from "@/components/NavBarRed2.vue";
import Footer from "@/components/Footer.vue";
export default {
  metaInfo: {
    title: "WeCare",
  },
  name: "Home",
  components: {
    NavWhite,
    NavRed,
    NavRed2,
    Footer,
  },
  mounted() {
    const body = document.body;
    const closeHamburger = document.querySelector(".MBIcon");
    const closeHamburger2 = document.querySelector(".MBIconRed");
    const closeHamburger3 = document.querySelector(".MBIconRed2");
    const btnHamburger = document.querySelector(".MenuIcon");
    const btnHamburger2 = document.querySelector(".MenuIconRed");
    const btnHamburger3 = document.querySelector(".MenuIconRed2");
    const overlay = document.querySelector(".MBLinksContainer");
    const overlay2 = document.querySelector(".MBLinksContainerRed");
    const overlay3 = document.querySelector(".MBLinksContainerRed2");

    closeHamburger3.addEventListener("click", function() {
      overlay3.classList.toggle("inactive");

      if (overlay3.classList.contains("inactive")) {
        btnHamburger3.classList.remove("open");
        document.body.classList.remove("no-scroll");
      }
    });

    closeHamburger2.addEventListener("click", function() {
      overlay2.classList.toggle("inactive");

      if (overlay2.classList.contains("inactive")) {
        btnHamburger2.classList.remove("open");
        document.body.classList.remove("no-scroll");
      }
    });

    closeHamburger.addEventListener("click", function() {
      overlay.classList.toggle("inactive");

      if (overlay.classList.contains("inactive")) {
        btnHamburger.classList.remove("open");
        document.body.classList.remove("no-scroll");
      }
    });

    window.addEventListener("scroll", () => {
      const scroller = document.querySelector(".eventscroll");
      const Fader1 = document.querySelector(".event1");
      const Fader2 = document.querySelector(".event2");
      const Fader3 = document.querySelector(".event3");
      const P1 = document.querySelector(".p1");
      const P2 = document.querySelector(".p2");
      const P3 = document.querySelector(".p3");
      const scrollable =
        document.documentElement.scrollHeight - window.innerHeight;
      const scrolled = window.scrollY;
      const scrolled1 = window.scrollY < 2200;
      const scrolled2 = window.scrollY > 3000;
      console.log();

      if (scrolled1) {
        P1.classList.add("fade-in");
        P2.classList.remove("fade-in");
        scroller.style.transform = "translate(0, 0px)";
      } else {
        P1.classList.remove("fade-in");
        P2.classList.add("fade-in");
        scroller.style.transform = "translate(0, 175px)";
      }
      if (scrolled2) {
        P3.classList.add("fade-in");
        P2.classList.remove("fade-in");
        scroller.style.transform = "translate(0, 335px)";
      } else {
        P3.classList.remove("fade-in");
      }
    });
    document.querySelector(".event1").addEventListener("click", () => {
      window.scrollTo(0, 1900);
    });
    document.querySelector(".event2").addEventListener("click", () => {
      window.scrollTo(0, 2750);
    });
    document.querySelector(".event3").addEventListener("click", () => {
      window.scrollTo(0, 3580);
    });
  },
};
</script>

<style lang="scss">
.inactive {
  transform: translateX(-100%);
  opacity: 0;
}
.active {
  transform: translateX(0);
}
.MBLinksContainer {
  background: url("../assets/wmenublack.png");
  background-color: white;
  background-size: 109%;
  background-position: center;
  background-repeat: no-repeat;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  display: flex;
  position: fixed;
  z-index: 99;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  transition: 0.8s cubic-bezier(0.2, 0.8, 0.2, 1);
}
.MBLogo {
  position: absolute;
  top: 15px;
  left: 30px;
}
.MBLogoRed {
  position: absolute;
  top: 15px;
  left: 30px;
}
.MBLogoRed2 {
  position: absolute;
  top: 15px;
  left: 30px;
}
.MBIconContainer {
  position: absolute;
  top: 29px;
  right: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.MBIconContainerRed {
  position: absolute;
  top: 29px;
  right: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.MBIconContainerRed2 {
  position: absolute;
  top: 29px;
  right: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.MBIcon {
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
    &:first-child {
      transform: translateY(7px) rotate(45deg);
    }

    &:nth-child(2) {
      transform: translateX(-20px);
      opacity: 0;
    }

    &:last-child {
      transform: translateY(-7px) rotate(-45deg);
    }
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
.MBIconRed {
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
    &:first-child {
      transform: translateY(7px) rotate(45deg);
    }

    &:nth-child(2) {
      transform: translateX(-20px);
      opacity: 0;
    }

    &:last-child {
      transform: translateY(-7px) rotate(-45deg);
    }
    width: 100%;
    height: 2px;
    background: #ffffff;
    border-radius: 5px;
    transition: opacity 500ms, transform 500ms;

    &:not(:first-child) {
      margin-top: 0.3125rem;
    }
  }
}
.MBIconRed2 {
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
    &:first-child {
      transform: translateY(7px) rotate(45deg);
    }

    &:nth-child(2) {
      transform: translateX(-20px);
      opacity: 0;
    }

    &:last-child {
      transform: translateY(-7px) rotate(-45deg);
    }
    width: 100%;
    height: 2px;
    background: #ffffff;
    border-radius: 5px;
    transition: opacity 500ms, transform 500ms;

    &:not(:first-child) {
      margin-top: 0.3125rem;
    }
  }
}
.MBLinks {
  position: absolute;
  bottom: 5%;
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
.MBLinksContainerRed {
  background: url("../assets/menuback.jpg");
  background-size: 109%;
  background-position: center;
  background-repeat: no-repeat;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  display: flex;
  position: fixed;
  z-index: 99;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  transition: 0.8s cubic-bezier(0.2, 0.8, 0.2, 1);
}
.MBLinksContainerRed2 {
  background: url("../assets/menuback.jpg");
  background-size: 109%;
  background-position: center;
  background-repeat: no-repeat;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  display: flex;
  position: fixed;
  z-index: 99;
  top: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  transition: 0.8s cubic-bezier(0.2, 0.8, 0.2, 1);
}
.MBLinksRed {
  position: absolute;
  bottom: 5%;
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
        color: white;
        font-size: 25px;
        font-weight: 600;
        letter-spacing: -1.5px;
      }
    }
    .mobiledonate {
      a {
        color: white;
      }
    }
    .mobilevol {
      a {
        color: white;
      }
    }
  }
}
.MBLinksRed2 {
  position: absolute;
  bottom: 5%;
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
        color: white;
        font-size: 25px;
        font-weight: 600;
        letter-spacing: -1.5px;
      }
    }
    .mobiledonate {
      a {
        color: white;
      }
    }
    .mobilevol {
      a {
        color: white;
      }
    }
  }
}

.header {
  position: relative;
  text-align: center;
  width: 80%;
  margin: 150px auto 200px auto;
  @media (min-width: 750px) {
    margin-top: 170px;
  }
  @media (min-width: 1024px) {
    text-align: left;
    margin: 100%;
    margin: 200px auto;
  }
  h1 {
    font-size: 2rem;
    font-weight: 600;
    color: #c41c48;
    line-height: 1;
    letter-spacing: -0.1rem;
    max-width: 650px;
    margin: 30px auto 0 auto;
    @media (min-width: 750px) {
      font-size: 2.5rem;
      margin-bottom: 30px;
      max-width: 400px;
    }
    @media (min-width: 1024px) {
      font-size: 3.5rem;
      max-width: 600px;
      margin: 0;
    }
    @media (min-width: 1400px) {
      font-size: 3.125rem;
      max-width: 500px;
      margin: 0;
    }
  }
  h4 {
    font-size: 1rem;
    line-height: 1.5;
    font-weight: 300;
    max-width: 250px;
    color: #212121;
    margin: 20px auto 60px auto;
    @media (min-width: 750px) {
      line-height: 1.2;
      font-size: 1.3rem;
      max-width: 350px;
    }
    @media (min-width: 1024px) {
      font-size: 1.25rem;
      max-width: 400px;
      margin: 30px 0 50px 0;
    }
  }
  .volunteers {
    font-size: 15px;
    font-weight: 300;
    letter-spacing: 0px;
    color: white;
    background: #c41c48;
    border-radius: 10px;
    padding: 1rem 1.375rem;

    &:hover {
      color: white;
      background: #911636;
    }
  }
}
.section2 {
  position: relative;
  height: 700px;
  background: #c41c48;
  overflow: visible;
  @media (min-width: 500px) {
    height: 1000px;
  }
  @media (min-width: 750px) {
    display: flex;
    height: 500px;
    justify-content: space-between;
    align-items: center;
  }
  @media (min-width: 1024px) {
    height: 700px;
    width: 100%;
  }
  @media (min-width: 1300px) {
    height: 1000px;
    width: 100%;
  }

  .l2l {
    margin-top: -100px;
    margin-left: 7.5%;
    width: 85%;
    @media (min-width: 750px) {
      margin-top: -100px;
      width: 45%;
    }
    @media (min-width: 1024px) {
      margin-top: -145px;
      margin-left: 7.5%;
      width: 45%;
    }
    @media (min-width: 1300px) {
      margin-top: -200px;
      margin-left: 7.5%;
      width: 45%;
    }
  }
  .section2text {
    margin-top: 30px;
    margin-left: 7.5%;
    text-align: left;

    @media (min-width: 750px) {
      margin-top: 0px;
    }
    @media (min-width: 1024px) {
      margin-left: 4%;
      width: 40%;
    }

    h2 {
      font-size: 2rem;
      font-weight: 600;
      line-height: 1;
      color: white;
      letter-spacing: -2px;
      width: 200px;
      font-weight: 600;
      @media (min-width: 750px) {
        font-size: 2rem;
      }
      @media (min-width: 1024px) {
        font-size: 2.5rem;
        width: 300px;
      }
      @media (min-width: 1300px) {
        font-size: 3.125rem;
        width: 400px;
      }
    }
    p {
      width: 90%;
      color: white;
      font-size: 1rem;
      line-height: 1.5;
      font-weight: 300;
      @media (min-width: 750px) {
        width: 90%;
      }
      @media (min-width: 1024px) {
        font-size: 1.25rem;
        width: 80%;
      }
    }
  }
}
.section3 {
  position: relative;
  @media (min-width: 1024px) {
    margin: 10px 0 10px 0%;
  }

  .section3title {
    margin-top: 100px;
    margin-left: 7.5%;
    @media (min-width: 750px) {
      margin-top: 50px;
      margin-left: 7.5%;
      @media (min-width: 1024px) {
        margin-top: 100px;
        margin-left: 7.5%;
      }
    }
    h1 {
      font-size: 2rem;
      letter-spacing: -2px;
      width: 200px;
      font-weight: 600;
      color: #c41c48;
      text-align: left;
      line-height: 1;
      width: 90%;
      margin-bottom: 40px;
      @media (min-width: 750px) {
        width: 60%;
      }
      @media (min-width: 1024px) {
        font-size: 3.125rem;
        width: 500px;
      }
    }
  }
  .event {
    display: flex;
    position: relative;
    width: 100%;

    justify-content: space-between;

    .escontainer {
      position: absolute;
      top: 60px;
      left: -10px;
    }
    .eventscroll {
      transform-origin: top;
      height: 100px;
      width: 4px;
      border-radius: 10px;
      background-color: #c41c48;
      transition: all 500ms;
    }
    .fade-in {
      color: black;
    }
    .fade-out {
      color: #bbbbbb;
    }
  }
  .events {
    @media (min-width: 1024px) {
      position: sticky;
      position: -webkit-sticky;
      top: 200px;
      text-align: left;
      width: 500px;
      align-self: start;
      margin-left: 7.5%;
      @media (max-width: 1250px) {
        top: 25%;
      }
      @media (min-width: 1400px) {
        top: 20%;
      }
    }
    .event1 {
      margin-top: 50px;
      margin-bottom: 50px;
      margin-left: 7.5%;
      cursor: pointer;

      &:hover {
        p {
          color: black;
        }
      }
    }
    .event2 {
      margin-top: 50px;
      margin-bottom: 50px;
      margin-left: 7.5%;
      cursor: pointer;
      &:hover {
        p {
          color: black;
        }
      }
    }
    .event3 {
      margin-top: 50px;
      margin-bottom: 50px;
      margin-left: 7.5%;
      cursor: pointer;
      &:hover {
        p {
          color: black;
        }
      }
    }
    img {
      width: 90%;
      margin-bottom: 20px;
      @media (min-width: 1024px) {
        display: none;
      }
    }
    h3 {
      font-size: 2rem;
      letter-spacing: -2px;
      line-height: 1;
      width: 70%;
      font-weight: 600;
      color: #c41c48;
      margin-bottom: 0;
      @media (min-width: 1024px) {
        width: 200px;
        font-size: 1.6rem;
        letter-spacing: -1px;
      }
    }
    p {
      width: 90%;
      color: #212121;
      font-size: 1rem;
      line-height: 1.5;
      font-weight: 300;
      transition: all 500ms ease-out;
      @media (min-width: 1024px) {
        font-size: 1rem;
        line-height: 1.3;
        width: 300px;
        color: #b3b3b3;
      }
    }
  }

  .images {
    display: none;
    @media (min-width: 1024px) {
      display: flex;
      width: 100%;
      flex-direction: column;
      justify-content: center;
      align-items: center;

      img {
        @media (max-width: 1250px) {
          width: 450px;
        }
        width: 615px;
      }
      :first-child {
        margin-top: 75px;
      }
      :last-child {
        margin-bottom: 150px;
      }
      :not(:last-child) {
        @media (max-width: 1250px) {
          margin-bottom: 80%;
        }
        margin-bottom: 300px;
      }
    }
  }
  .line {
    margin: 0px auto 0 auto;
    height: 1px;
    background-color: #21212167;
    width: 85%;
    @media (min-width: 1024px) {
      width: 80%;
    }
  }
  .sec3text {
    margin-top: 40px;
    margin-left: 7.5%;
    margin-bottom: 20px;
    @media (min-width: 1024px) {
      margin-left: 0;
    }
    .sectext {
      @media (min-width: 1024px) {
        display: flex;
        justify-content: space-evenly;
      }
    }

    h1 {
      font-size: 2rem;
      letter-spacing: -2px;
      line-height: 1;
      width: 90%;
      font-weight: 600;
      color: #c41c48;
      @media (min-width: 750px) {
        width: 70%;
      }
      @media (min-width: 1024px) {
        width: 50%;
      }
      @media (min-width: 1300px) {
        width: 40%;
      }
    }
  }

  .gallerylink {
    margin-top: 40px;
    margin-bottom: 90px;
    .gallery {
      margin-top: 20px;
      font-size: 15px;
      font-weight: 300;
      letter-spacing: 0px;
      color: white;
      background: #c41c48;
      border-radius: 10px;
      padding: 1rem 1.375rem;
    }
  }
}
.section4 {
  position: relative;
  height: 320px;
  padding-top: 250px;
  background: url("../assets/prefooter.jpg");
  background-color: #c41c48;
  background-size: 120%;
  background-repeat: no-repeat;
  background-position: top;
  @media (min-width: 750px) {
    background-size: 100%;
    height: 600px;
  }
  @media (min-width: 1250px) {
    padding-top: 500px;
    background-size: 100%;
    height: 650px;
  }
}
.sec4 {
  text-align: center;
  margin-left: 0%;
  .Don {
    text-align: center;
    margin: 0px 0 100px 0;
    @media (min-width: 750px) {
      margin-bottom: 80px;
    }
    @media (min-width: 1024px) {
      margin-bottom: 125px;
    }
    h1 {
      text-align: center;
      // margin-left: 7.5%;
      margin: 50px auto 40px auto;

      font-size: 2rem;
      letter-spacing: -2px;
      font-weight: 600;
      color: white;
      line-height: 1;
      width: 90%;

      @media (min-width: 1024px) {
        width: 45%;
      }
    }
    a {
      margin-top: 20px;
      font-size: 15px;
      font-weight: 300;
      letter-spacing: 0px;
      color: #c41c48;
      background: white;
      border-radius: 10px;
      padding: 1rem 3rem;
    }
  }
}
</style>
