<template>
  <div class="widget">
    <div class="widget__form">
      <label>
        <input type="text" id="longUrl" placeholder="Long URL (required)"/>
      </label>
      <label>
        <input type="text" id="keyword" placeholder="Short URL keyword (optional)"/>
      </label>
      <label>
        <input type="checkbox" id="private"/>
        <span>Private?</span>
      </label>
      <button type="submit">Shorten</button>
    </div>
    <ui-listing></ui-listing>
  </div>
</template>

<script>
  import Listing from './Listing';

  export default{
    data(){
      return {}
    },
    components: {
      'ui-listing': Listing
    }
  }
</script>

<style>
  .widget {
    background: #eeeeee;
    padding: 50px 100px 50px 50px;
  }

  .widget__form {
    display: flex;
    align-items: center;
    margin-bottom: 60px;
  }

  .widget__form label {
    width: 40%;
    margin-right: 15px;
  }

  .widget__form label:last-of-type {
    width: auto;
  }

  .widget__form label input {
    width: 100%;
    color: #555555;
    font-size: 14pt;
    padding: 2px 7px;
  }

  .widget__form label input[type="checkbox"] {
    width: auto;
  }

  .widget__form label input[type="checkbox"] + span {
  }

  .widget__form label input[type="checkbox"]:checked + span {
  }

  .widget__form button {
    background: #2979bc;
    color: #ffffff;
    border-radius: 3px;
    border: 1px solid #555555;
    font-size: 14pt;
    cursor: pointer;
  }
</style>
