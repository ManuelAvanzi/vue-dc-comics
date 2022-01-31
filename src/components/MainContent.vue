<template>
    <div id="container">
       
       <div v-for="(fumetto, index) in fumetti" :key="index" class="card">
           <img :src="fumetto.thumb"/>
           <h3>{{fumetto.series.toUpperCase()}}</h3>
       </div>
    </div>
</template>

<script>
export default {

    

    props:{
      fumetti: Array
    }
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';
#container{
    
    max-width: 1200px;
    height: 600px;
    background-color: $grey;
    margin:0 auto;

    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    

    .card{
        width: 180px;
        text-align: center;
        padding:20px;
        margin:2px;

        img{
            width: 100%;
        }
    }

    h3{
        color:white;
        font-size:14px;
    }
    

    h1{
        color:$blue;
        text-align: center;
        line-height: 350px;

    }
}
</style>