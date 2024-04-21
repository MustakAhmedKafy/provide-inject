<script setup>
import course from "./data/course.js";
</script>

<template>
  <div>
    <p>Our Course from Component D: {{ course.name }}</p>
    <input type="text" v-model="course.name" />
  </div>
</template>
