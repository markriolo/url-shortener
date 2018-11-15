<template>
  <div class="listItem">
    <a href="#" target="_blank" title="Lorem Ipsum">Lorem ipsum dolor sit amet</a>
    <span>1 week ago</span>
    <p>http://example.com/example/page</p>
  </div>
</template>

<script>
  export default{
    data(){
      return {}
    }
  }
</script>

<style>
  .listItem {
    width: 100%;
    max-width: 100%;
    background: #ffffff;
    border: 1px solid #555555;
    text-align: left;
    padding: 15px;
    border-collapse: collapse;
    margin-top: -1px;
  }

  .listItem a {
    margin-bottom: 10px;
    display: block;
  }

  .listItem span {
    margin-bottom: 3px;
  }

  .listItem p {
    margin: 0;
  }
</style>
