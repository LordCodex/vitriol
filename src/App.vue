<template>
 
  <HeaderNew/>
  <AboUt/>
</template>

<script>
import HeaderNew from './components/Header.vue'
import AboUt from './components/About.vue'
export default {
  name: 'App',
  components: {
    HeaderNew,
    AboUt,
  }
}
</script>

<style>
*{
  margin: 0;
  box-sizing: border-box;
  list-style-type: none;
  text-decoration: none;
  font-family: Roboto, sans-serif;
  padding: 0;
}
html{
  font-size: 14px;
}
</style>
