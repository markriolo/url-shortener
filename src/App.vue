<template>
  <div id="app">
    <ui-header></ui-header>
    <ui-widget></ui-widget>
  </div>
</template>

<script>
  import Header from './components/Header';
  import Widget from './components/Widget';

  export default {
    data () {
      return {}
    },
    components: {
      'ui-header': Header,
      'ui-widget': Widget
    }
  }
</script>

<style>
  *{
    box-sizing: border-box;
  }
  body{
    margin: 0;
    width: 100%;
  }
  #app {
    font-family: 'Source Sans Pro', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #555555;
    font-size: 14pt;
  }

  h1 {
    font-size: 22pt;
    font-weight: bold;
  }

  a {
    font-size: 18pt;
    font-weight: normal;
    text-decoration: underline;
    color: #2979bc;
  }

</style>
