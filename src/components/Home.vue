<template>
  <div class="home">
    <h1>Holly's Landing Page Container</h1>
    <div class='container'>
      <ul>
        <li><i class='fas fa-angle-right'></i>One</li>
        <li><i class='fas fa-angle-right'></i>Two</li>
        <li><i class='fas fa-angle-right'></i>Three</li>
        <li><i class='fas fa-angle-right'></i>Four</li>
        <li><i class='fas fa-angle-right'></i>Five</li>
      </ul>
    </div>
  </div>
</template>

<script>
  export default {
    'name': 'Home'
  }
</script>

<style scoped>
  @import "https://cdn.jsdelivr.net/npm/animate.css@3.5.2/animate.min.css";
  @import "https://use.fontawesome.com/releases/v5.3.1/css/all.css";

  ul {
    margin: 0;
    padding: 0;
    text-align: left;
    list-style-type: none;
  }

  ul li {
    padding-top: 25px;
    font-size: 1.25em;
    margin-bottom: 2px;
    
  }

  i {
    padding-right: 10px;
    cursor: pointer;
  }
</style>
