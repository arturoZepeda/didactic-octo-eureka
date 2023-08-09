<script setup>
import Cabecera from './components/Header.vue';
import Cuerpo from './components/Body.vue';
import Info from './components/Info.vue';
import Habilidades from './components/Habilidades.vue';
</script>

<template>
  <section id="main">
    <Cabecera />
    <Cuerpo  />
  </section>
  <aside id="sidebar">
    <Info />
    <Habilidades />
  </aside>
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
