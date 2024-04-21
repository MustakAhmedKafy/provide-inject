<script setup>
import course from "./data/course.js";
import ComponentE from "./ComponentE.vue";
</script>

<template>
  <div>
    <p>Our Course from Component D: {{ course.name }}</p>
    <ComponentE />
  </div>
</template>
