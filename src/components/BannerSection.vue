<template>
  <div class="banner">
      <div class="container">
        <div class="container__flex banner_black">
          <div class="container__wrapper_width_2">
            <img src="./assets/hero-image.webp" alt="">
          </div>
          <div class="container__wrapper_width_2">
            <h2 class="banner__offer">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
            </h2>
            <div class="banner__text">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
              tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
              quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
              consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
              cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
              proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: 'BannerSection',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.banner {
  background: #ebd7c1;
}
.banner_black {
    background: #2a2625;
    border-radius: 30px;
    padding: 5% 2%;
    color: #fff;
}
.banner__text {
  color: #fff;
}
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 5%;
}
.container_height_100vh {
  height: 100vh;
  display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
}
.container__flex, .hero__item, .footer__social {
  display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    justify-content: space-between;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    align-items: center;
}
.container_color_black {
  background: #2a2625;
    border-radius: 30px;
    position: relative;
    margin-top: 250px;
    height: 500px;
}
.container__wrapper_width_2 {
  width: 50%;
  margin: 20px 0px;
}
.container__wrapper_width_3 {
  width: 28%;
  margin: 20px 0px;
}
.container__wrapper_width_4 {
  width: 24%;
  margin: 20px 0px;
}

</style>
