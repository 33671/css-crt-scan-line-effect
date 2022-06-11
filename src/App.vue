<script>
export default {
  setup() {
    return {
      text: `主啊！是时候了。夏日曾经很盛大<br>
把你的阴影落在日晷上<br>
让秋风刮过田野<br>
让最后的果实长得丰满<br>
再给它们两天南方的气候<br>
迫使它们成熟<br>
把最后的甘甜酿入浓酒<br>
谁这时没有房屋，就不必建筑<br>
谁这时孤独，就永远孤独<br>
就醒着，读着，写着长信<br>
在林荫道上来回<br>
不安地游荡，当着落叶纷飞<br>`,
      text2: "游戏结束",
    };
  },
};
</script>
<template>
  <div class="scanlines">
    <!-- IMG -->
    <div class="sacnlines-container">
      <div
        class="jpg"
        style="
          display: flex;
          justify-content: center;
          flex-wrap: wrap;
          align-items: center;
        "
      >
        <div
          v-html="text"
          class="text"
          style="width: 100%; text-align: center; line-height: 50px"
        ></div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
@import "./assets/scaning-line.scss";
.jpg {
  background: url(./assets/87882344_p0.jpg) no-repeat;
  background-size: cover;
  width: 100%;
  height: 100vh;
  border: none;
}
.text {
  font-family: ZpixReviewLocal;
  font-size: 25px;
  color: aliceblue;
}
body {
  margin: 0;
  padding: 0;
  position: relative;
  text-shadow: 2px 2px 2px #333;
}
@font-face {
  font-family: ZpixReviewLocal;
  src: url(./assets/zpix.woff2);
}
</style>
