<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>
    <h2>PHP is the best language of the world!</h2>
    <input type="text" v-model = "message">
    <span v-text = "message"></span>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Hello Vue!',
      message:''
    }
  }
}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
