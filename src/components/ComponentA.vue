<script setup>
import { inject, provide } from "vue";
import ComponentB from "./ComponentB.vue";

const course = inject("course");

provide("course-stock", 500);
</script>

<template>
  <div>
    <p>Our Course Name component A: {{ course.name }}</p>

    <ComponentB />
  </div>
</template>
