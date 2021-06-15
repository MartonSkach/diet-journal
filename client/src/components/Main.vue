<template>
  <div class="main">
    <Header/>
    <Menu/>
    <Content/>
    <div>Footer</div>
  </div>


</template>

<script>
import Header from './Header/Header.vue'
import Menu from './Menu/Menu.vue'
import Content from './Content/Content.vue'

export default {
  components: {
    Header,
    Menu,
    Content
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


</style>

<!-- 
Main colors
0C0A3E
7B1E7A
B33F62
F9564F
F3C677
-->
