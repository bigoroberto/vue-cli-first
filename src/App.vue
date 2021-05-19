<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TitleHeader />
    <Jumbotrone />
  </div>
</template>

<script>
import TitleHeader from '@/components/TitleHeader.vue'
import Jumbotrone from '@/components/Jumbotrone.vue'

export default {
  name: 'App',
  components: {
    TitleHeader,
    Jumbotrone
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
