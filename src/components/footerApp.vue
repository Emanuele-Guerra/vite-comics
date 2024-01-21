<script>
     export default{
    name: "footerApp",
    data (){
        return{
            
        }
    },
   }
</script>

<template>
<div class="bg-wrap">
    <section class="ft-container">
     <section class="list-wrap">
        <div class="ft-wrap">
            <div class="inlineB">
           <ul>
            <li><h3>DC COMICS</h3></li>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
           </ul> 
        </div>
        
        <div class="inlineB">
            <ul>
                <li><h3>DC</h3></li>
                <li>Terms Of Use</li>
                <li>Privacy Policy (New)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent Workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>
            </ul>
        </div>
        <div class="inlineB">
            <ul>
                <li><h3>SITES</h3></li>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
                
            </ul>
        </div>
        <div class="li-base">
            <ul>
                <li><h3>SHOP</h3></li>
                <li>Shop DC</li>
                <li>Shop DC Collectibles</li>
            </ul>
        </div>
        </div>
        <div>
            <img src="" alt="">
        </div>
     </section>
    </section>
</div>
   
   
    

</template>

<style scoped>
    .ft-container{
        position: relative;
        background-image: url(img/dc-logo-bg.png);
        background-size: 30%;
        background-repeat: no-repeat;
        background-position: 85% 60%;
        z-index: 0;
        height: 40vh;
    }
    li{
        color: grey;
    }
    h3{
        color: white;
    }
    .list-wrap{
        width: 80%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        padding-top: 2rem;
    }
    ul{
        margin:  0 1.3rem;
        list-style: none;
        font-size: 10px;
        line-height: 15px;
        
    }
    .inlineB{
        display: inline-block;
    }
    .ft-wrap{
        display: flex;
        flex-wrap: wrap;
        width: 30%;
        position: relative;
    }
    img{
        position: absolute;
        right: 15rem;
        top: -100px;
        z-index: -1;
        width: 500px;
        
        
    }
    .li-base{
        top: 9rem;
        position: absolute;
    }
    .bg-wrap{
        background-image: url(img/footer-bg.jpg);
    }
</style>