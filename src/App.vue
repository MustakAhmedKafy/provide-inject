<script setup>
import { reactive, provide } from "vue";
import ComponentA from "./components/ComponentA.vue";
import ComponentD from "./components/ComponentD.vue";
// import course from "./components/data/course.js";
const course = reactive({
  price: 299,
  name: "vue 3",
});

provide("course", course);
</script>

<template>
  <div>
    <ComponentA />
    <ComponentD />
  </div>
</template>
