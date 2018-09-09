<template lang="pug">
  h1 
    span(class='box') {{ message }}
</template>


<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        message: 'Hello, world'
      };
    }
  };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" scoped>
  .box
    border 1px dashed pink
    padding 1.5rem
    border-radius 15px
</style>

