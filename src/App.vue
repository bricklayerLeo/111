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

<style lang="scss" scoped>
@function p2r($size){
    @return ($size/32)*1rem;
}




</style>
