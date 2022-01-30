<template>
    <div id="container-list">
      <div class="box-list">
        <div class="list-section a">
            <ul>
                <h1 class="title">DC COMICS</h1>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
            </ul>
            <ul>
                <h1 class="title">DC COMICS</h1>
                <li>shop DC</li>
                <li>Shop DC Collectibles</li>
                
            </ul>
        </div>
        <div class="list-section b">
            <ul>
                <h1 class="title">DC</h1>
                <li>Terms of Use</li>
                <li>Privacy</li>
                <li>Ad choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscription</li>
                <li>Talent workshop</li>
                <li>Ad choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscription</li>
                <li>Contact Us</li>
            </ul>
            
        </div>
         <div class="list-section c">
            <ul>
                <h1 class="title">SITES</h1>
                <li>DC</li>
                <li>Mad magazine</li>
                <li>DC kids</li>
                <li>DC universe</li>
                <li>DC power visa</li>
                
            </ul>
            
        </div>
     </div>
     <div class="img-container">
         <img id="dc-logo" src="../assets/dc-logo-bg.png" alt="">
     </div>
    </div>
    
</template>


<script>
export default {
    
}
</script>



<style lang="scss" scoped>
@import '@/style/variables.scss';

#container-list{

img{
    width: 400px;
    margin-left:240px;
}
    
    display: flex;
    width: 100%;
    height: 400px;
    background-image: url("../assets/footer-bg.jpg");
    background-size: cover;
    
    h1{
        color:white;
        margin-left:12px;
        font-size: 22px;
    }
    li{
        color:grey;
        margin:12px;
        font-size: 11px;
        font-weight: lighter;
        cursor: pointer;

         &:hover{
             color:$blue;
                   
            }
    }

    .box-list{
        display: flex;
        
        margin-left: 100px;
        
        width: 500px;
        .list-section{
            margin-top:20px;
            margin:40px;
        }

        

    }
    
}

</style>