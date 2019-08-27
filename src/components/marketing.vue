<template>
  <div class="marketingBlock">
    <h2>Profitable Affiliate Marketing</h2>
    <h3>
      There are many offers in traffic arbitrage.
      <br />Make profit, work with CPA#1
    </h3>
    <div class="items relative">
      <div class="item">
        <h4>
          Who we
          <span class="gradientText">are</span>
        </h4>
        <p>Team of professionals who speak with you on the same language</p>
        <div class="svgBox svgLeft">
          <img src="../assets/left.svg" alt />
        </div>
        <div class="svgBox svgRight">
          <img src="../assets/right.svg" alt />
        </div>
      </div>
      <div class="item">
        <h4>
          Who we
          <span class="gradientText">work for</span>
        </h4>
        <p>We work for beginners and experienced arbitrageurs and webmasters</p>
      </div>
      <div class="item">
        <h4>Our advantage</h4>
        <p>Payouts are often higher than competitors</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "marketing"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import url("https://fonts.googleapis.com/css?family=Muli:400,700,900&display=swap");
* {
  padding: 0;
  margin: 0;
}

.marketingBlock {
  padding-top: 135px;
  font-family: "Muli";
}
.marketingBlock h2 {
  font-style: normal;
  font-weight: 900;
  font-size: 52px;
  line-height: 120%;
  /* or 62px */
  text-align: center;
  margin-bottom: 30px;
}

.marketingBlock h3 {
  font-family: Muli;
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 150%;
  /* or 36px */
  text-align: center;
  margin-bottom: 40px;
}
.items {
  display: flex;
  justify-content: space-between;
}
.item {
  padding: 20px 30px;
  box-sizing: border-box;
  width: 350px;
  height: 229px;
  background: #ffffff;
  box-shadow: 0px 0px 20px #e1e4ed;
  border-radius: 10px;
}
.item h4 {
  font-style: normal;
  font-weight: bold;
  font-size: 22px;
  line-height: 24px;
  margin-bottom: 25px;
  color: #3c09b3;
}

.gradientText {
  background: linear-gradient(
    163.6deg,
    #3c09b3 12.95%,
    #d43f4f 80.35%,
    #f4c545 197.24%
  );
  -webkit-background-clip: text;
  color: transparent;
}

.item p {
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 25px;
  color: #716c80;
}
.svgBox {
  position: absolute;
  z-index: -1;
  height: 130px;
  width: 130px;
}

.relative {
  position: relative;
  z-index: 1;
}
.svgLeft {
  top: 195px;
  left: 40px;
}
.svgRight {
  top: 195px;
  left: 247px;
}

@media screen and (max-width: 1200px) {
  .marketingBlock h2 {
    font-size: 32px;
  }
  .item {
    width: 30%;
    height: auto;
    padding-bottom: 30px;
  }

  .marketingBlock h3 {
    font-size: 19px;
  }

  .item h4 {
    font-size: 16px;
    line-height: 24px;
    margin-bottom: 15px;
  }

  .item p {
    font-size: 10px;
    line-height: 16px;
  }

  .svgLeft {
    top: 122px;
    left: -5px;
  }
  .svgRight {
    top: 120px;
    left: 145px;
  }

  .svgLeft img {
    width: 100px;
    height: 100px;
  }
  .svgRight img {
    width: 100px;
    height: 100px;
  }
}

@media screen and (max-width: 768px) {
  .marketingBlock h2 {
    font-size: 24px;
  }
  .item {
    width: 30%;
    height: auto;
    padding-bottom: 20px;
  }

  .marketingBlock h3 {
    font-size: 15px;
  }

  .item h4 {
    font-size: 14px;
    line-height: 24px;
    margin-bottom: 15px;
  }

  .item p {
    font-size: 10px;
    line-height: 16px;
  }

  .svgLeft {
    top: 149px;
    left: -52px;
  }
  .svgRight {
    top: 142px;
    left: 85px;
  }

  .svgLeft img {
    width: 100px;
    height: 100px;
  }
  .svgRight img {
    width: 100px;
    height: 100px;
  }
}

@media screen and (max-width: 1200px) {
  .marketingBlock h2 {
    font-size: 32px;
  }
  .item {
    width: 30%;
    height: auto;
    padding-bottom: 30px;
  }

  .marketingBlock h3 {
    font-size: 19px;
  }

  .item h4 {
    font-size: 16px;
    line-height: 24px;
    margin-bottom: 15px;
  }

  .item p {
    font-size: 10px;
    line-height: 16px;
  }

  .svgLeft {
    top: 122px;
    left: -5px;
  }
  .svgRight {
    top: 120px;
    left: 145px;
  }

  .svgLeft img {
    width: 100px;
    height: 100px;
  }
  .svgRight img {
    width: 100px;
    height: 100px;
  }
}

@media screen and (max-width: 576px) {

  .marketingBlock{
    padding-top: 100px;
  }

  .marketingBlock h2 {
  margin-bottom: 10px;
}

.marketingBlock h3 {
  margin-bottom: 17px;
}
  .items {
    flex-wrap: wrap;
    justify-content: flex-end;
  }

  .marketingBlock h2 {
    font-size: 14px;
  }
  .item {
    width:45%;
    margin-right: 10px;
    margin-bottom: 10px;
  }

  .marketingBlock h3 {
    font-size: 9px;
  }

  .item h4 {
    font-size: 10px;
    line-height: 12px;
    margin-bottom: 7px;
  }

  .item p {
    font-size: 7px;
    line-height: 16px;
  }

  .svgLeft {
    top: 80px;
    left: 15px;
  }
  .svgRight {
    top: 90px;
    left: 95px;
  }

  .svgLeft img {
    width: 70px;
    height: 70px;
  }
  .svgRight img {
    width: 50px;
    height: 50px;
  }
}
</style>
