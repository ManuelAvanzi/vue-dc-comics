<template>
    <div id="footer-container">
        <div class="stripe-container">
            <nav>
                <ul>
                    <li><img src="../assets/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span></li>
                </ul>
                <ul>
                    <li><img src="../assets/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span></li>
                </ul>
                <ul>
                    <li><img src="../assets/buy-comics-shop-locator.png" alt="">
                    <span>SUBSCRIPTION</span></li>
                </ul>
                <ul>
                    <li><img src="../assets/buy-comics-subscriptions.png" alt="">
                    <span>COMIC SHOP LOCATOR</span></li>
                </ul>
                <ul>
                    <li><img src="../assets/buy-dc-power-visa.svg" alt="">
                    <span>DC POWER VISA</span></li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

#footer-container{ 
    width:100%;
    
   .stripe-container{
       width: 100%;
       height: 150px;
       padding:20px;
       background-color: $stripeblue;

       nav{
           display: flex;
           justify-content: center;
       }
       img{
           width: 50px;
           
           line-height: 120px;
       }
       span{
           color:white;
           text-align: center;
       }
       
       ul{
           list-style: none;
           li{
               
               padding:5px;
               line-height: 150px;
               margin:5px;
               span{
                   line-height: 100px;
                  
                   margin-bottom: 30px;
               }

                &:hover{
                     color:$blue;
                    
                    }


           }
       }



   }
}
</style>