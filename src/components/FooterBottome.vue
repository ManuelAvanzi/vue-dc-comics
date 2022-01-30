<template>
    <div class="container">

     <div class="button"><h1>SIGN-UP NOW!</h1></div>
     <div class="social-container">
         <span>FOLLOW US</span>
         <img src="../assets/footer-facebook.png" alt="">
         <img src="../assets/footer-periscope.png" alt="">
         <img src="../assets/footer-pinterest.png" alt="">
         <img src="../assets/footer-twitter.png" alt="">
         <img src="../assets/footer-youtube.png" alt="">


     </div>

    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

.container{
    display: flex;
    justify-content: space-between;
    width: 100%;
    
    background-color: $grey;

    .button{
    margin-left: 130px;
    margin-top:30px;
    margin-bottom:30px;
        h1{
            color:white;
            font-size: 15px;
        }
        width: 180px;
        border:3px solid $stripeblue;
        padding:20px;
        text-align: center;

    }
    .social-container{
        display: flex;
        
        width: 500px;
        justify-content: space-between;
        margin-right:10px;
        img{
            width: 60px;
        }
        
        
        margin-top:30px;
         margin-bottom:30px;
        span{
            color:$stripeblue;
            font-size: 15px;
            font-weight: bold;
            line-height: 60px;
            
        }
    }
}


</style>
