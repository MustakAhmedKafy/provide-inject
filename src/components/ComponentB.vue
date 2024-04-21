<script setup>
import { inject } from "vue";
import ComponentC from "./ComponentC.vue";

const course = inject("course");
</script>

<template>
  <div>
        <p>Our Course Name component B: {{ course.name }}</p>
    <ComponentC />
  </div>
</template>
