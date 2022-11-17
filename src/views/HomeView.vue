<template>
  <div>
    <div class="big-box">
      <div class="top">
        <div class="top-left"></div>
        <div class="top-right">
          <div class="top-right-left">
            <div class="top-right-left-top"></div>
            <div class="top-right-left-bttm"></div>
          </div>
          <div class="top-right-right">
            <div class="top-right-right-top"></div>
            <div class="top-right-right-bttm"></div>
          </div>
        </div>
      </div>
      <div class="bottom">
        <div class="bttm-left">
          <div class="bttm-left-left"></div>
          <div class="bttm-left-right"></div>
        </div>
        <div class="bttm-right"></div>
      </div>
    </div>
  </div>
</template>

<style>
.big-box {
  background-color: grey;
  height: 100vh;
  width: 100vw;
  justify-content: center;
  align-content: center;
}

.box {
  display: flex;
  justify-content: center;
  align-content: center;
  width: 100vw;
  max-width: 1100px;
  height: 100vh;
  max-height: 1100px;
  background-color: #a91cc9;
}
.top {
  background-color: rgb(0, 149, 255);
  height: 60%;
  display: flex;
}
.bottom {
  background-color: pink;
  height: 40%;
  display: flex;
}
.top-left {
  width: 60%;
  background-color: blue;
  border: 2px solid black;
  border-radius: 20px;
  padding: 5px;
}
.top-right {
  width: 40%;
  background-color: rgb(0, 255, 225);
  display: flex;
}
.bttm-left {
  width: 60%;
  background-color: #a91cc9;
  display: flex;
}
.bttm-right {
  width: 40%;
  background-color: bisque;
  border: 2px solid black;
  border-radius: 20px;
  padding: 5px;
}
.bttm-left-left {
  width: 50%;
  background-color: fuchsia;
  border: 2px solid black;
  border-radius: 20px;
  padding: 5px;
}
.bttm-left-right {
  width: 50%;
  background-color: yellow;
  border: 2px solid black;
  border-radius: 20px;
  padding: 5px;
}
.top-right-left {
  width: 50%;
  background-color: green;
  display: flex;
  flex-direction: column;
}
.top-right-right {
  width: 50%;
  background-color: green;
  display: flex;
  flex-direction: column;
}
.top-right-left-top {
  height: 50%;
  width: 100%;
  background-color: lime;
  border: 2px solid black;
  border-radius: 20px;
  padding: 5px;
}
.top-right-left-bttm {
  height: 50%;
  width: 100%;
  background-color: rgb(255, 0, 51);
  border: 2px solid black;
  border-radius: 20px;
  padding: 5px;
}
.top-right-right-top {
  height: 50%;
  width: 100%;
  background-color: rgb(42, 91, 12);
  border: 2px solid black;
  border-radius: 20px;
  padding: 5px;
}
.top-right-right-bttm {
  height: 50%;
  width: 100%;
  background-color: rgb(0, 128, 255);
  border: 2px solid black;
  border-radius: 20px;
  padding: 5px;
}
</style>

<script>
export default {
  data: function () {
    return {
      // message: "Welcome",
    };
  },
  created: function () {},
  methods: {},
};
</script>
