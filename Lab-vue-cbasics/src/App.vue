<script setup>

import NavBarCom from './components/NavBarCompo.vue';
import FooterCompo from './components/FooterCompo.vue';
import Exo2 from './components/Exo2.vue';
import Exo3 from './components/Exo3.vue';
import Exo4 from './components/Exo4.vue';

</script>

<template>
  
  <NavBarCompo />
  <Exo2 />
  <hr />
  <Exo3 />
  <hr />
  <Exo4 />
  <hr />
  
 
  <FooterCompo />

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
