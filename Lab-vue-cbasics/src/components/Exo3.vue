<template>

<div id="v-if-v-else">
    <h1 v-if="propertyShow">
      Trying
    </h1>
    <h1 v-else>
      what else
    </h1>
  </div>
  <div id="v-show">
    <h1 v-show="showProperty">
      espetial things
    </h1>
  </div>
  <div id="v-if-conditional">
    <h1 v-if="showProperty2 === true">
      yes of course
    </h1>
  </div>
  
</template>

<script setup>
import { ref } from "vue";

const propertyShow = ref(false);
const showProperty = ref(false);
const showProperty2 = ref(true);
</script>

<style scoped>
    
</style>