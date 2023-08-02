<script setup lang="ts">
import WeatherReport from "./components/WeatherReport.vue";
</script>

<template>
  <WeatherReport :coords="{ latitude: 0, longitude: 0 }"/>
</template>

<style scoped>
</style>
