<template>
 
  <HeaderNew/>
  <AboUt/>
  <MaJor/>
  <Blog/>
  <Footer/>
</template>

<script>
import MaJor from './components/Major.vue'
import HeaderNew from './components/Header.vue'
import AboUt from './components/About.vue'
import Blog from './components/Blog.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    HeaderNew,
    AboUt,
    MaJor,
    Blog,
    Footer,
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
