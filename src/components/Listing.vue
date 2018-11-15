<template>
  <div class="listing">
    <h1>Recent links</h1>
    <div class="listing__table">
      <list-item></list-item>
      <list-item></list-item>
      <list-item></list-item>
      <list-item></list-item>
    </div>
  </div>
</template>

<script>
  import ListItem from './ListItem';

  export default{
    data(){
      return {}
    },
    components: {
      'list-item': ListItem
    }
  }
</script>

<style scoped>
  h1{
    text-align: left;
  }
  .listing__table{
    width: 100%;
    max-width: 100%;
  }
</style>
