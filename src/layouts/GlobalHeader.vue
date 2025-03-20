<template>
  <div class="globalheader">
    <div @click="goto('/')">
      <img src="../assets/logo-text.png" alt="" />
    </div>
    <div class="route">
      <button @click="goto('/learning')">Learning</button>
      <button @click="goto('/tools')">Tools</button>
      <button @click="goto('/packages')">Packages</button>
      <button @click="goto('/community')">Community</button>
      <button @click="goto('/play')">Play</button>
    </div>
    <div class="search"></div>
  </div>
</template>

<script lang="ts" setup>
import { useRouter } from "vue-router";
const router = useRouter();
const goto = (link: string) => {
  router.push(link);
};
</script>

<style scoped>
.globalheader {
  display: flex;
  background-color: #cccccc;
  background-image: url(../assets/background/header.jpg);
  height: 100px;
  justify-content: center;
  align-content: center;
}
.globalheader img {
  height: 100px;
  width: 210px;
  margin-left: 10px;
}
.globalheader .route {
  display: flex;
  flex: auto;
  font-size: 23px;
  margin: 50px;
  align-items: center;
  justify-content: space-evenly;
}
.globalheader .route button {
  margin: 10px;
}
.globalheader .search {
  width: 200px;
}
</style>
