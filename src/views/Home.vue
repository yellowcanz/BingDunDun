<template>
  <div class="dundun">
    <span class="dundun body"></span>
    <span class="bgmask"></span>
    <span class="ear ear-l"></span>
    <span class="ear-l seo"></span>
    <span class="ear ear-r"></span>
    <span class="ear-r seo"></span>
    <span class="hand-l"></span>
    <span class="hand-l seo"></span>
    <span class="hand-r"></span>
    <span class="hand-r seo">
      <svg viewBox="0 0 532 532">
        <path id="heart" transform="translate(10, 10)" d="M256,96.5l-19.7-20.3C186.1,24.3,104.5,15.9,49.7,62.6c-62.8,53.6-66.1,149.8-9.9,207.9l193.5,199.8 c12.5,12.9,32.8,12.9,45.3,0l193.5-199.8c56.3-58.1,53-154.3-9.8-207.9l0,0C407.5,15.9,326,24.3,275.7,76.2L256,96.5z" />
      </svg>
    </span>
    <span class="foot foot-l"></span>
    <span class="foot-l seo"></span>
    <span class="foot foot-r"></span>
    <span class="foot-r seo"></span>
    <span class="face">
      <span class="eyes eyes-l">
        <span class="eyeball eyeball-l"></span>
      </span>
      <span class="eyes eyes-r">
        <span class="eyeball eyeball-r"></span>
      </span>
      <span class="nose"></span>
      <span class="mouth"></span>
    </span>
    <img src="../assets/1.png" />
    <span class="line line1"></span>
    <span class="line line2"></span>
    <span class="line line3"></span>
    <span class="line line4"></span>
    <span class="line line5"></span>
    <span class="line line6"></span>
    <span class="line line7"></span>
    <span class="line line8"></span>
    <span class="line line9"></span>
    <span class="line line10"></span>
    <span class="line line11"></span>
    <span class="line line12"></span>
    <span class="line line10"></span>
  </div>
</template>

<style scoped>
.dundun {
  position: relative;
  width: 200px;
  height: 230px;
  border-radius: 65% 65% 55% 55%;
}
.dundun.body {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 10;
  border: 5px solid #393939;
  box-shadow: 0 0 0 3px #fff, 0 0 0 5px #393939;
  background-color: #ffffff;
}
.bgmask {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  border-radius: 65% 65% 55% 55%;
  width: 190px;
  height: 220px;
  background-color: #ffffff;
  z-index: 15;
}
.ear {
  position: absolute;
  top: 5px;
  width: 50px;
  height: 60px;
  background-color: #393939;
  border-radius: 50%;
  box-shadow: 0 0 0 3px #fff, 0 0 0 5px #393939;

  z-index: 5;
}
.ear-l {
  left: 5px;
}
.ear-l.seo {
  position: absolute;
  top: 5px;
  width: 50px;
  height: 60px;
  background-color: #393939;
  border-radius: 50%;
  box-shadow: none;
  z-index: 10;
}
.ear-r {
  right: 5px;
}
.ear-r.seo {
  position: absolute;
  top: 5px;
  width: 50px;
  height: 60px;
  background-color: #393939;
  border-radius: 50%;
  box-shadow: none;
  z-index: 10;
}
.hand-l {
  position: absolute;
  left: 0;
  top: 55%;
  width: 35px;
  height: 75px;
  border: 1px solid #393939;
  border-radius: 0% 100% 60% 60%;
  transform: rotate(30deg);
  transform-origin: 50% 0;
  background-color: #393939;
  box-shadow: 0 0 0 3px #fff, 0 0 0 5px #393939;
  z-index: 1;
}
.hand-l.seo {
  z-index: 11;
  box-shadow: none;
}
.hand-r {
  position: absolute;
  right: -5px;
  top: 70%;
  width: 40px;
  height: 100px;
  border: 1px solid #393939;
  border-radius: 100% 45% 80% 80%;
  transform: rotate(205deg);
  transform-origin: 50% 0;
  background-color: #393939;
  box-shadow: 0 0 0 3px #fff, 0 0 0 5px #393939;
  z-index: 1;
}
.hand-r.seo {
  z-index: 11;
  box-shadow: none;
}
svg {
  position: absolute;
  bottom: 10px;
  right: 10px;
  width: 20px;
  z-index: 10;
  transform: rotate(-185deg);
}
#heart {
  fill: #b52430;
}
.foot {
  position: absolute;
  width: 50px;
  height: 80px;
  border: 1px solid #393939;
  border-radius: 0% 0% 10% 25%;
  background-color: #393939;
  box-shadow: 0 0 0 3px #fff, 0 0 0 5px #393939;
  z-index: 1;
}
.foot-l.seo {
  position: absolute;
  width: 50px;
  height: 80px;
  border: 1px solid #393939;
  border-radius: 0% 0% 10% 25%;
  background-color: #393939;
  z-index: 10;
}

.foot-l {
  bottom: -40px;
  left: 35px;
}
.foot-l::after {
  position: absolute;
  content: '';
  right: -2px;
  bottom: -1px;
  width: 10px;
  height: 10px;
  background-color: #ffffff;
  border: 1px solid #393939;
  border-radius: 0 50% 40% 0;
  background-color: #393939;
  border-left: none;
  border-top: none;
}
.foot-r {
  bottom: -40px;
  right: 35px;
  transform: rotateY(180deg);
}
.foot-r.seo {
  position: absolute;
  width: 50px;
  height: 80px;
  border: 1px solid #393939;
  border-radius: 0% 0% 10% 25%;
  background-color: #393939;
  z-index: 10;
}

.foot-r::after {
  position: absolute;
  content: '';
  right: -2px;
  bottom: -1px;
  width: 10px;
  height: 10px;
  background-color: #ffffff;
  border: 1px solid #393939;
  border-radius: 0 50% 40% 0;
  background-color: #393939;
  border-left: none;
  border-top: none;
}

.face {
  position: absolute;
  top: 8%;
  left: 50%;
  transform: translateX(-50%);
  width: 170px;
  height: 130px;
  border: 3px solid #94bd75;
  box-shadow: inset 0 0 0 3px #ebc472, inset 0 0 0 6px #68739d, inset 0 0 0 9px #933471, inset 0 0 0 12px #85bae9;
  border-radius: 100% 100% 80% 80%;
  z-index: 18;
}

.eyes {
  position: absolute;
  top: 30px;
  width: 35px;
  height: 50px;
  border-radius: 50%;
  border: 1px solid #393939;
  background-color: #393939;
  z-index: 20;
}

.eyes-l {
  left: 20px;
  transform: rotate(45deg);
}
.eyeball {
  position: absolute;
  content: '';
  width: 20px;
  height: 20px;
  border-radius: 50%;
  border: 1px solid #393939;
  box-shadow: 0 0 0 2px #fff;
  background-color: #393939;
  z-index: 10;
}
.eyeball-l {
  top: 10px;
  left: 8px;
}
.eyeball::after {
  position: absolute;
  content: '';
  width: 6px;
  height: 6px;
  border-radius: 50%;
  background-color: #fff;
  z-index: 20;
}
.eyeball-l::after {
  top: 1px;
  left: 50%;
  transform: translateX(-50%);
}
.eyeball-r::after {
  top: 50%;
  right: 1px;
  transform: translateY(-50%);
}
.eyes-r {
  right: 20px;
  transform: rotate(-45deg);
}
.eyeball-r {
  top: 10px;
  right: 8px;
}

.nose {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 20px;
  height: 15px;
  background-color: #393939;
  border-radius: 20% 20% 50% 50%;
  z-index: 20;
}
.mouth {
  position: absolute;
  bottom: 15px;
  left: 50%;
  transform: translateX(-50%) rotate(-5deg);
  width: 50px;
  height: 45px;
  border-radius: 45%;
  background-color: #393939;
}
.mouth::after {
  position: absolute;
  content: '';
  top: -1px;
  left: 49%;
  transform: translateX(-50%);
  width: 35px;
  height: 12px;
  border-radius: 50%;
  background-color: #fff;
}
.mouth::before {
  position: absolute;
  content: '';
  bottom: 3px;
  left: 49%;
  transform: translateX(-50%);
  width: 35px;
  height: 18px;
  border-radius: 50%;
  background-color: #b62532;
}

img {
  position: absolute;
  bottom: 10px;
  left: 50%;
  transform: translateX(-50%);
  width: 60px;
  /* height: 101px; */
  z-index: 20;
}

.line {
  position: absolute;
  top: 10px;
  left: 47px;
  background-color: #fff;
  z-index: 30;
}
.line1 {
  width: 2.8px;
  height: 4px;
  top: 10px;
  left: 47px;
  transform: rotate(-48deg);
}
.line2 {
  width: 3px;
  height: 5px;
  top: 52.4px;
  left: 8px;
  border-radius: 35% 35% 0% 0%;
  transform: rotate(-36deg);
}
.line3 {
  width: 3px;
  height: 5px;
  top: 9px;
  left: 150.8px;
  border-radius: 35% 35% 0% 0%;
  transform: rotate(48deg);
}
.line4 {
  width: 3px;
  height: 5px;
  top: 52.4px;
  left: 189px;
  border-radius: 35% 35% 0% 0%;
  transform: rotate(40deg);
}
.line5 {
  width: 2.6px;
  height: 8px;
  top: 77.5px;
  left: 200px;
  border-radius: 35% 35% 0% 0%;
  transform: rotate(40deg);
}
.line6 {
  width: 2.4px;
  height: 6px;
  top: 152.8px;
  left: 200.6px;
  border-radius: 10% 0% 25% 0%;
  transform: rotate(47deg);
}
.line7 {
  width: 3px;
  height: 9px;
  top: 122px;
  left: -6px;
  border-radius: 0% 0% 0% 0%;
  transform: rotate(28deg) translateY(-1px);
}
.line8 {
  width: 3px;
  height: 6px;
  top: 180px;
  left: 5px;
  border-radius: 0% 0% 50% 0%;
  transform: rotate(35deg) translate(-0.1px, -1px);
}
.line9 {
  width: 3px;
  height: 6px;
  top: 213px;
  left: 32px;
}
.line10 {
  width: 3px;
  height: 6px;
  top: 230px;
  left: 85px;
}
.line11 {
  width: 3px;
  height: 6px;
  top: 230px;
  left: 112px;
}
.line12 {
  width: 3px;
  height: 6px;
  top: 213px;
  left: 165px;
}
</style>
