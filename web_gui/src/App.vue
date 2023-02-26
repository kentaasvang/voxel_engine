<script setup lang="ts">
  
      import init from "@/pkg/voxel_engine.js";
      init().then(() => {
          console.log("WASM Loaded");
      });

</script>

<template>
  <canvas></canvas>
</template>

<style scoped>

  canvas {
      background-color: black;
  }

</style>
