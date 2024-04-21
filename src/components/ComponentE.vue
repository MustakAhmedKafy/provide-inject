<script setup>
import course from "./data/course.js";
import ComponentF from "./ComponentF.vue";
</script>

<template>
  <div>
    <p>Our Course from Component E: {{ course.name }}</p>
    <ComponentF />
  </div>
</template>
