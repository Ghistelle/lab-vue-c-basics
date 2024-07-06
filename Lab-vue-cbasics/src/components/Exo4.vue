
<template>

<div v-for="(post, index) in posts" :key="index">
    <ul>
      <li>
        <h3>{{ index }} - {{ post.title }}</h3>
        <h5>{{ post.description }}</h5>
        <p>{{ post.content }}</p>
      </li>
    </ul>
  </div>
  
</template>


<script setup>

import { ref } from "vue";

const posts = ref([
  {
    title: "Hungry and tired ",
    description:
      "the brain stop and he fell ; he was working on his project and did'nt have time to eat",
    content: "they chould fine something to eat",
  },
  {
    title: "Legislative",
      
    description: 
    "Font National or Font Populaire;Who gonna win elections?",
    content: "The best will get it",
  },
  {
    title: "A la recherche du bonheur? ",
    description: "how hard work can pay",
    content: "he had finally get the job",
  },
]);
</script>


<style scoped>
li {
  margin: 2rem 0;
  list-style: none;
}
</style>