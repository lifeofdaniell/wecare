<template>
  <div class="layout">
    <slot />
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>
<script>
export default {
  components: {},
};
</script>
<style lang="scss">
html {
  scroll-behavior: smooth;
  @media (max-width: 780px) {
    height: 100%;
    overflow: hidden;
  }
}
@font-face {
  font-family: GT Walsheim Pro;
  src: url("../assets/GTWalsheimPro-UltraBold.ttf");
  font-weight: 800;
}
@font-face {
  font-family: GT Walsheim Pro;
  src: url("../assets/GTWalsheimPro-Black.ttf");
  font-weight: 700;
}
@font-face {
  font-family: GT Walsheim Pro;
  src: url("../assets/GTWalsheimPro-Bold.ttf");
  font-weight: 600;
}
@font-face {
  font-family: GT Walsheim Pro;
  src: url("../assets/GTWalsheimPro-Medium.ttf");
  font-weight: 500;
}
@font-face {
  font-family: GT Walsheim Pro;
  src: url("../assets/GTWalsheimPro-Regular.ttf");
  font-weight: 400;
}
@font-face {
  font-family: GT Walsheim Pro;
  src: url("../assets/GTWalsheimPro-Light.ttf");
  font-weight: 300;
}
@font-face {
  font-family: GT Walsheim Pro;
  src: url("../assets/GTWalsheimPro-Thin.ttf");
  font-weight: 200;
}
@font-face {
  font-family: GT Walsheim Pro;
  src: url("../assets/GTWalsheimPro-UltraLight.ttf");
  font-weight: 100;
}

body {
  box-sizing: border-box;
  font-family: GT Walsheim Pro;
  margin: 0;
  padding: 0;
  line-height: 1.2;
  background: white;
  text-decoration: none;
  @media (max-width: 780px) {
    height: 100%;
    overflow: auto;
  }
}

a {
  text-decoration: none;
}
.no-scroll {
  overflow: hidden;
}
</style>
