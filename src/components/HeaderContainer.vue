<template>
    <header>
        <div class="headerbox">
            <div class="menu-container">

                <div class="logo-container">
                    <img src="../assets/dc-logo.png" alt=""/>
                </div>

                <nav>
                    <ul>
                        <li>CHARACTERS</li>
                        <li>COMICS</li>
                        <li>MOVIES</li>
                        <li>TV</li>
                        <li>GAMES</li>
                        <li>COLLECTIBLES</li>
                        <li>VIDEOS</li>
                        <li>FANS</li>
                        <li>NEWS</li>
                        <li>SHOP</li>
                    </ul>
                </nav>
            </div>
        </div>

        <div class="jumbotron">
            
        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

header {
    flex-wrap: wrap;
  
  .jumbotron{
   background-image: url("../assets/jumbotron.jpg");
   background-size: cover;
   width: 100%;
   height: 290px;
}
    background-color: white;

    .logo-container{
        padding:10px;

        img{
            margin-left:170px;
            width: 70px;
            
        }
    }

    .menu-container{
        
        display: flex;
        justify-content: space-between;
        align-items: center;
        

        nav{
            margin-left:110px;
            margin-right:150px;
            
            width: 800px;
            

            ul{
                list-style: none;
                display: flex;
                justify-content: center;

                li{
                    font-size:13px;
                    padding:10px;
                    cursor: pointer;
                    
                    
                
                   &:hover{
                     color:#47a4fa;
                     border-bottom: 3px solid #47a4fa;
                    }

                }
            }
        }
    }


}

</style>