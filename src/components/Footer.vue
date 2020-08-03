<template>
  <div>
    <div class="sec4b">
      <div class="footer">
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
        <p>love. care. share.</p>
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
  height: 350px;
  // text-align: center;
  padding-top: 50px;
  .footer {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    width: 65%;
    margin-left: 7.5%;

    .col1 {
      // margin-left: 7.5%;
      ul {
        margin: 0;
        padding: 0;
        li {
          &:not(:first-child) {
            margin-top: 25px;
          }
          list-style: none;
          text-decoration: none;
          a {
            color: white;
            font-weight: 400;
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
            margin-top: 25px;
          }
          list-style: none;
          text-decoration: none;
          a {
            color: white;
            font-weight: 400;
          }
        }
      }
    }
  }
}
.footext {
  margin-top: 70px;
  text-align: center;
  // margin-left: 7.5%;
  p {
    margin: 0;
    font-size: 0.8rem;
    font-weight: 300;
    color: rgba(255, 255, 255, 1);
  }
  h4 {
    color: rgba(255, 255, 255, 0.7);
    font-size: 0.8rem;
    letter-spacing: px;
    margin: 5px 0 0px 0;
    font-weight: 300;
  }
}
</style>
