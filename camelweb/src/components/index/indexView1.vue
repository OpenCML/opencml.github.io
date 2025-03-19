<template>
  <div class="indexView1 slide-fwd-center">
    <v-card class="card hvr-grow-shadow" elevation="16">
      <v-card-item>
        <v-card-title style="font-size: 45px"> Camel </v-card-title>
        <v-card-subtitle style="font-size: 23px">
          <b>面向AI时代的下一代编程语言</b>
        </v-card-subtitle>
      </v-card-item>

      <v-card-text style="font-size: 23px">
        &ensp;&ensp;&ensp;
        Camel是一个基于图的、多阶段的、类型驱动的特定领域语言（DSL），旨在弥合AI研究与生产部署之间的差距。
        <br />&ensp;&ensp;&ensp;
        它结合了函数式编程的优雅和声明式编程的表达力。它提供了天生的异步语义和高度可定制的图操作，使开发者能够编写高级代码，该代码编译后具有接近原生的性能。
      </v-card-text>
    </v-card>
    <v-card class="card hvr-grow-shadow" elevation="16">
      <v-card-item>
        <v-card-title> Card title </v-card-title>
      </v-card-item>

      <v-card-text>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua.
      </v-card-text>
    </v-card>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.indexView1 {
  display: flex;
  justify-content: space-evenly;
}
.card {
  margin: 20px;
  margin-top: 80px;
  padding: 40px;
  border-radius: 20px;
  width: 550px;
  height: 600px;
  background-color: #1bb8eb;
}

@keyframes slide-fwd-center {
  from {
    transform: translateX(0%); /* 动画开始时的位置 */
    opacity: 0.3; /* 动画开始时的透明度 */
  }
  to {
    transform: translateX(0); /* 动画结束时的位置 */
    opacity: 0.8; /* 动画结束时的透明度 */
  }
}
.slide-fwd-center {
  animation: slide-fwd-center 3s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
}
</style>
