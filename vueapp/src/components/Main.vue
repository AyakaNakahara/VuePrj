<template>
  <div class="main">
    <h1>備 忘 録.</h1>
    <div class="disp">
    <img width="200px" src="../assets/boook.png" alt="">
    <span>今まで行った環境構築とかつまりポイントとかのメモ用。</span>
    </div>
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
    color: #c0b283;
    text-align: center;
}
h2{
  color: #373737;
}
.main{
    background-color: #f4f4f4;
    height: 200px;
    padding-top: 50px;
}
.disp{
  display: flex;
  align-items: center;
  justify-content: space-around;
}
</style>