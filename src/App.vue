<template>
 
  <HeaderNew/>
</template>

<script>
import HeaderNew from './components/Header.vue'
export default {
  name: 'App',
  components: {
    HeaderNew,
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
}
html{
  font-size: 14px;
}
</style>
