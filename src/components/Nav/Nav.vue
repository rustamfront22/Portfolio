<template>
  <div class="header">
    <div class="header-content container">
      <div class="pyramid-loader">
        <div class="wrapper">
          <span class="side side1"></span>
          <span class="side side2"></span>
          <span class="side side3"></span>
          <span class="side side4"></span>
          <span class="shadow"></span>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { Icon } from "@iconify/vue";
import { createApp, ref, onMounted } from "vue";


</script>

<style>
#game-board {
  width: 600px;
  height: 400px;
  border: 1px solid black;
}

.snake {
  width: 20px;
  height: 20px;
  background-color: green;
}

.food {
  width: 20px;
  height: 20px;
  background-color: red;
}
</style>
