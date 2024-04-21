<script setup>
import { reactive,provide } from "vue";
import ComponentA from "./components/ComponentA.vue";
const course = reactive({
  price: 299,
  name: "vue 3",
});

provide('course',course)
</script>

<template>
  <div>
    <ComponentA />
  </div>
</template>
