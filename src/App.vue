<template>
  <div id="app">

    
    <br>
    <f/>
    
  </div>
</template>

<script>
import login from "./component/login.vue"
export default {
  data () {
    return {
      msg: 'Hello Vue!'
    }
  },
  components:{'f':login}
}
</script>

<style>
body {
  font-family:  Helvetica, sans-serif;
}
</style>
