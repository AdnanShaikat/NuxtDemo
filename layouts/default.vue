<template>
  <div class="container bg-white py-4 px-8">
    <AppHeader />
    <Nuxt />
  </div>
</template>

<script>
import AppHeader from  '../components/AppHeader.vue'
export default {
  components: {
    AppHeader
  }
};
</script>

<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1rem;
  line-height: 1.6;
  background: #f4f4f4;
}

a {
  color: #666;
  text-decoration: none;
}

ul {
  list-style: none;
}
</style>
