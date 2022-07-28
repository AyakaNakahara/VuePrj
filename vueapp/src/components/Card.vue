<template>
<div class="wrapper">
<a href="../Detail.vue">
  <div class="main">
    <h2>Title.</h2>
    <span>section.</span>
  </div>
</a>
</div>
</template>

<script>
export default {
  name: 'Main',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
    color: #373737;
    text-align: center;
}
.wrapper{
  width: 25%;
}
.main{
    background-color: #dcd0c0;
    height: 200px;
    width: 100%;
    margin-top: 50px;
    padding: 20px;
    border-radius: 30px;
    box-shadow: 5px 5px 10px rgba(55, 55, 55, 0.524);
}
</style>