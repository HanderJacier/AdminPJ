<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://vite.dev" target="_blank">
      <img src="./assets/440144479_2178280532517235_2890867806589985999_n.jpg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/99-anh-meme-meo-anh-che-meo-hai-de-thuong-cho-dien-thoai-may-tinh-1658116837-10.jpeg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Hoa Xuân APP" />
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
