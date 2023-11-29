<script>
     export default{
    name: "bannerApp",
    data (){
        return{
            bannerContent: [
                {
                    img:"img/buy-comics-digital-comics.png",
                    directory:"DIGITAL COMICS"
                },
                {
                    img:"img/buy-comics-merchandise.png",
                    directory:"DC MERCHANDISE"
                },
                {
                    img:"img/buy-comics-subscriptions.png",
                    directory:"SUBSCRIPTION"
                },
                {
                    img:"img/buy-comics-shop-locator.png",
                    directory:"COMIC SHOP LOCATOR"
                },
                {
                    img:"img/buy-dc-power-visa.svg",
                    directory:"DC POWER VISA"
                },
            ]
        }
    },
   }
</script>

<template>
    <section>
        <div class="wrapper">
            <div v-for="i in bannerContent">
                <div class="inside-wrapper">
                    <img :src="i.img" alt="">
                    <p>{{ i.directory }}</p>
                    
                </div>
            </div>
        </div>
            
            
        
    </section>
</template>

<style scoped>
    section{
        font-size: 12px;
        color: white;
        background-color: #0C7CEC;
        
    }
    img{
        width: 40px;
        max-height: 50px;
        margin-right: 0.5rem;
    }
    img:hover{
        scale: 1.2;
    }
   
    .wrapper{
        margin: 0 auto;
        width: 70%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 140px;
    }
    .inside-wrapper{
        display: flex;
        align-items: center;
    }
</style>