<template>
  <div class="title">✨ 关键特性</div>
  <div class="indexView3">
    <div class="content"><b>1. 基于图的语法</b></div>
    <div class="demo hvr-grow-shadow">
      <img src="../../assets/demo/demo1.jpg" alt="" />
    </div>
    <div class="demo hvr-grow-shadow">
      <img src="../../assets/demo/demo2.jpg" alt="" />
    </div>
    <div class="content"><b>2. 多阶段编程</b></div>

    <div class="content"><b>3. 天生的异步语义</b></div>
    <div class="demo hvr-grow-shadow">
      <img src="../../assets/demo/demo3.jpg" alt="" />
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.indexView3 {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.title {
  font-size: 40px;
  color: white;
  margin-top: 50px;
  margin-left: 20px;
  background-color: #00dbde;
  background-image: linear-gradient(90deg, #00dbde 0%, #fc00ff 100%);
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
.content {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 30%;
  height: 430px;
  margin: 30px;
  font-size: 30px;
  background-color: #21d4fd;
  background-image: linear-gradient(19deg, #21d4fd 0%, #b721ff 100%);
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
.demo {
  width: 825px;
  height: 430px;
  margin: 30px;
}
</style>
