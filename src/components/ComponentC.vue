<script setup>
import { inject } from "vue";

const course = inject("course");
const stock = inject("course-stock");
</script>

<template>
  <div>
    <p>Our Course Name component C: {{ course.name }}</p>
    <input type="text" v-model="course.name" />

    <p>Course Stock: {{ stock }}</p>
  </div>
</template>
