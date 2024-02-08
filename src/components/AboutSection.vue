<template>
<div class="about">
  <div class="container">
        <div class="title">About us</div>
        <div class="about__text">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
          tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
          quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
          consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
          cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
          proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
          tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
          quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
          consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
          cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
          proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
          tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
          quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
          consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
          cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
          proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
          tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
          quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
          consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
          cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
          proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
          tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
          quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
          consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
          cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
          proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
      </div>
      </div>
</template>

<script>
export default {
  name: 'AboutSection',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body {
.button_green {
  text-align: center;
}
.button_green a {
  background: #55b158;
  font-family: 'Bebas Neue', cursive;
}
.about {
  background: #ebd7c1;
}
  font-family: 'Roboto', sans-serif;
    font-weight: 400; 
    line-height: 1.4;
    font-size: 14px;
  color: #1d1d1d;
    background: #ebd7c1;
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
  width: 32%;
  margin: 20px 0px;
}
.container__wrapper_width_4 {
  width: 24%;
  margin: 20px 0px;
}
.title {
  color: #f44336;
    text-align: center;
    font-size: 40px;
    padding: 20px 0px;
    font-family: 'Bebas Neue', cursive;
}
.subtitle {
  padding: 10px 0px;
    text-align: center;
    color: #f44336;
    font-size: 20px;
    letter-spacing: 5px;
    font-family: 'Bebas Neue', cursive;
}
</style>
