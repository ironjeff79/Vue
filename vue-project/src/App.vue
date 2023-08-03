<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(15)
</script>

<template>
  <div class="card">
    <button type="button" @click="count--" >minus from {{ count }}</button>
    
  </div>

    <div id="app">
      <h1>hello world </h1>
    </div>
    <p>
    访问
    <a href="https://www.google.com/?hl=zh-CN" target="_blank">Google</a>
    
  </p>


</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  /*header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }*/
}
</style>
