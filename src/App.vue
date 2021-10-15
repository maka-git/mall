<template>
  <div id="app">
    <div class="hh">world
      <div class="ww">hello</div>
    </div>
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
.hh{
  font-size: 10px;
  /* .ww{
    font-size: 15px;
  } */
}
</style>
