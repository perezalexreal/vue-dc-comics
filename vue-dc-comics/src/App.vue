<template>
  <div id="app">
    <HeaderBox/>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'

export default {
  name: 'App',
  components: {
    HeaderBox
  }
}
</script>

<style lang="scss">

@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap'); 

* {
  padding: 0px ;
  margin: 0px ;
  box-sizing: border-box;
font-family: 'Roboto', sans-serif;
}
</style>
