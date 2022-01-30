<template>
    <div id="container">
        <h1>HELLO</h1>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
#container{
    border:1px solid white;
    width:100%;
    height: 350px;
    background-color: $grey;

    h1{
        color:$blue;
        text-align: center;
        line-height: 350px;

    }
}
</style>