<template>
  <div>
    <div class="sec4b">
      <img class="mlogo" alt="weCare logo" src="../assets/wecarelogowhite.png" width="35" />
      <p>love. care. share.</p>
      <div class="footer">
        <div class="footextdsk">
          <img alt="weCare logo" src="../assets/wecarelogowhite.png" width="60" />
          <p>love. care. share.</p>
          <h4>All Rights Reserved &#169; 2020 WeCare.</h4>
          <!-- <p>Designed and Built by Areola Daniel</p> -->
        </div>
        <div class="col1">
          <ul>
            <li>
              <g-link>Volunteer</g-link>
            </li>
            <li>
              <g-link>Donate</g-link>
            </li>
            <li>
              <g-link>Fundraise</g-link>
            </li>
            <li>
              <g-link>Partnerships</g-link>
            </li>
            <li>
              <g-link>Careers</g-link>
            </li>
          </ul>
        </div>
        <div class="col2">
          <ul>
            <li>
              <g-link>About</g-link>
            </li>
            <li>
              <g-link>Contact Us</g-link>
            </li>
            <li>
              <g-link>Instagram</g-link>
            </li>
            <li>
              <g-link>Twitter</g-link>
            </li>
            <li>
              <g-link>Media Kit</g-link>
            </li>
          </ul>
        </div>
      </div>
      <div class="footext">
        <h4>All Rights Reserved &#169; 2020 WeCare.</h4>
        <!-- <p>Designed and Built by Areola Daniel</p> -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
.sec4b {
  margin: 60px 0 0 0;
  background-color: #111111;
  height: 360px;
  // text-align: center;
  padding-top: 40px;
  .mlogo {
    margin-left: 7.5%;
    opacity: 0.7;
    margin-bottom: 0;
    @media (min-width: 1024px) {
      display: none;
    }
  }
  p {
    @media (min-width: 1024px) {
      display: none;
    }
    margin: 0px 0 30px 7.5%;
    font-size: 0.8rem;
    font-weight: 300;
    color: rgba(255, 255, 255, 0.7);
  }
  @media (min-width: 1024px) {
    background: url("../assets/footerimage.png");
    background-position-x: right;
    background-repeat: no-repeat;
    background-color: black;
    background-size: 100%;
  }
  .footer {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    width: 55%;
    margin-left: 7.5%;
    margin-top: 35px;
    @media (min-width: 1024px) {
      margin-top: 80px;
      width: 45%;
      justify-content: space-around;
      justify-items: center;
      align-items: flex-end;
    }
    .footextdsk {
      text-align: left;

      @media (max-width: 1023px) {
        display: none;
      }
      img {
      }
      p {
        margin: 10px 0 10px 0;
        font-size: 1rem;
        letter-spacing: -1px;
        font-weight: 300;
        color: rgba(255, 255, 255, 1);
      }
      h4 {
        color: rgba(255, 255, 255, 0.7);
        font-size: 0.8rem;
        letter-spacing: px;
        margin: 5px 0 0px 0;
        font-weight: 300;
        @media (min-width: 1250px) {
          margin-bottom: 5px;
        }
      }
    }

    .col1 {
      // margin-left: 7.5%;
      ul {
        margin: 0;
        padding: 0;
        li {
          &:not(:first-child) {
            margin-top: 20px;
          }
          list-style: none;
          text-decoration: none;
          a {
            color: white;
            font-weight: 400;
            &:hover {
              color: #c41c48;
            }
          }
        }
      }
    }
    .col2 {
      // margin-left: 20%;
      ul {
        margin: 0;
        padding: 0;
        li {
          &:not(:first-child) {
            margin-top: 20px;
          }
          list-style: none;
          text-decoration: none;
          a {
            color: white;
            font-weight: 400;
            &:hover {
              color: #c41c48;
            }
          }
        }
      }
    }
  }
}
.footext {
  margin-top: 40px;
  text-align: left;
  margin-left: 7.5%;
  @media (min-width: 1024px) {
    display: none;
  }

  h4 {
    color: rgba(255, 255, 255, 0.7);
    font-size: 0.8rem;
    letter-spacing: px;
    margin: 0px 0 0px 0;
    font-weight: 300;
    @media (min-width: 1250px) {
      margin-bottom: 5px;
    }
  }
}
</style>
