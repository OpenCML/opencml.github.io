<template>
  <GlobalHeader />
  <router-view></router-view>
</template>

<script lang="ts" setup>
import GlobalHeader from "./layouts/GlobalHeader.vue";
import "../src/styles/animation.css";
import "./styles/global.css";
</script>
