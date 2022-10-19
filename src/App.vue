<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
*{
    margin: 0;
    padding: 0;
}
html{
    height: 100%;
}
body{
    height: 100%;
    width: 100%;
    background-color: rgba(133, 197, 234, 0.7);
    background-image:url(./assets/Trees-23.jpg);
    
}
</style>
