<template>
<div class="hero">
<div class="container container_height_100vh">
  <div class="container__flex">
    <div class="container__wrapper_width_2">
      <h1 class="hero__title">
        Coffee shop
      </h1>
      <div class="hero__subtitle">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      </div>
      <div class="hero__list">
        <div class="hero__item">
          <div><img class="hero__icon" src="@/src/assets/img/hero-item-icon-1.webp" alt=""></div>
          <div class="hero__item__text">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
          </div>
        </div>
        <div class="hero__item">
          <div><img class="hero__icon" src="@/assets/hero-item-icon-2.webp" alt=""></div>
          <div class="hero__item__text">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
          </div>
        </div>
        <div class="hero__item">
          <div><img class="hero__icon" src="@/assets/hero-item-icon-3.webp" alt=""></div>
          <div class="hero__item__text">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
          </div>
        </div>
      </div>
      <div class="button">
        <a href="#products">Go to shop</a>
      </div>
    </div>
    <div class="container__wrapper_width_2">
      <div class="hero__image">
        <img src="@/assets/hero-image.webp" alt="Cup of coffee">
      </div>
    </div>
  </div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'HeroSection',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
.hero {
	height: 100vh;
	position: relative;
	background: #ebd7c1;
}
.hero__title {
	font-size: 45px;
	font-weight: 900;
	padding: 10px 0px;
	font-family: 'Bebas Neue', cursive;
}
.hero__icon {
	width: 70px;
    background: #fff;
    padding: 15px;
    border-radius: 50%;
    box-shadow: 0px 6px 16px #bfae9b;
    margin: 0px 15px 0px 0px;
}
.hero__image {
    height: 100vh;
    background: #55b158;
    top: 0;
    border-radius: 0px 0px 0px 250px;
    border-radius: 52% 48% 30% 70% / 51% 54% 46% 49%;
}
.hero__image img {
	top: 25%;
    position: relative;
}
.button {
	margin: 30px 0px;
}
.button a {
	background: #f44336;
    color: #fff;
    padding: 15px 40px;
    font-size: 20px;
    letter-spacing: 3px;
    border-radius: 30px;
    box-shadow: 0px 7px 11px #5f5f5fb8;
    font-family: 'Bebas Neue', cursive;
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
