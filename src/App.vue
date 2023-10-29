<script setup>
import Navbar from './components/Navbar';
export default {
  name: 'app',
  components: {
    Navbar
  },
};
</script>

<template>
  <div id="app">
    <header>
      <Navbar />
    </header>
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'montserrat', sans-serif;
}
header {
  width: 100vh;
  background-color: #222;
  padding: 25px;
}
</style>
