<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }} and chose ur prey</button>
    <p>
      Tonight
      <code>VUE</code> HUNT!
    </p>
  </div>

  <!-- <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p> -->
  <p>
    Install
    <img src="https://ddragon.leagueoflegends.com/cdn/img/champion/splash/Rengar_40.jpg" target="_blank">MIAOH
    <!-- in your IDE for a better ma anche no -->
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
