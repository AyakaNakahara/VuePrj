<template>
<div>
<Main />
<Content>
    <div class="disp">
        <Card />
        <Card />
        <Card />
    </div>
    <div class="disp">
        <Card />
        <Card />
        <Card />
    </div>
</Content>
</div>
</template>

<script lang="ts">
import Main from './Main.vue'
import Content from './Content.vue'
import Card from './Card.vue'
export default  {
name: 'Index',
components: {
    Main,
    Content,
    Card,
},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.disp{
    display: flex;
    justify-content: space-around;
}
</style>
