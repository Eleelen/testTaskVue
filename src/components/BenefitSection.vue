<template>
<div class="benefit">
      <div class="container">
        <div class="container__flex">
          <div class="container__wrapper_width_3 benefit__wrapper">
            <img class="benefit__icon" src="./images/benefit-icon-img-1.webp" alt="">
            <div class="benefit__text">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
              tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
            </div>
          </div>
          <div class="container__wrapper_width_3 benefit__wrapper">
            <img class="benefit__icon" src="./images/benefit-icon-img-2.webp" alt="">
            <div class="benefit__text">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
              tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
            </div>
          </div>
          <div class="container__wrapper_width_3 benefit__wrapper">
            <img class="benefit__icon" src="./images/benefit-icon-img-3.webp" alt="">
            <div class="benefit__text">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
              tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: 'BenefitSection',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.benefit {
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
  width: 28%;
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
.benefit__wrapper {
  
    margin: 20px 0px;
    background: #ffffff69;
    border-radius: 30px;
    padding: 20px;
    box-shadow: 4px 4px 15px #5c5c5c7a;
}
.benefit__icon {
  width: 80px;
    margin: 10px auto;
    padding: 20px;
    border-radius: 50%;
    box-shadow: 0px 0px 20px grey;
}
</style>
