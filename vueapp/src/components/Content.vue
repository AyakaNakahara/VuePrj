<template>
  <div class="main">
    <h1>Contents.</h1>
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'Content',
  components: {
},
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
    color: #c0b283;
    text-align: center;
}
.main{
    background-color: #f4f4f4;
    height: 100vh;
    padding-top: 200px;
}
</style>