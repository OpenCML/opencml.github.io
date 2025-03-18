<template>
  <div class="indexView1">
    <v-card class="card" elevation="16">
      <v-card-item>
        <v-card-title style="font-size: 40px"> Camel </v-card-title>
        <v-card-subtitle style="font-size: 20px">
          <b>面向AI时代的下一代编程语言</b>
        </v-card-subtitle>
      </v-card-item>

      <v-card-text style="font-size: 20px">
        Camel是一个基于图的、多阶段的、类型驱动的特定领域语言（DSL），旨在弥合AI研究与生产部署之间的差距。它结合了函数式编程的优雅和声明式编程的表达力。它提供了天生的异步语义和高度可定制的图操作，使开发者能够编写高级代码，该代码编译后具有接近原生的性能。
      </v-card-text>
    </v-card>
    <v-card class="card" elevation="16">
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
  width: 450px;
  height: 500px;
  background-color: #5b788a;
}
</style>
