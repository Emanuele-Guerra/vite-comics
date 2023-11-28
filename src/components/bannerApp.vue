<script>
     export default{
    name: "bannerApp",
    data (){
        return{
            bannerContent: [
                {
                    img:"../assets/img/buy-comics-digital-comics.png",
                    directory:"DIGITAL COMICS"
                },
                {
                    img:"../assets/img/buy-comics-merchandise.png",
                    directory:"DC MERCHANDISE"
                },
                {
                    img:"../assets/img/buy-comics-subscriptions.png",
                    directory:"SUBSCRIPTION"
                },
                {
                    img:"../assets/img/buy-comics-shop-locator.png",
                    directory:"COMIC SHOP LOCATOR"
                },
                {
                    img:"../assets/img/buy-dc-power-visa.svg",
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
                <div>
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
        width: 60px;
    }
    .wrapper{
        margin: 0 auto;
        width: 70%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 140px;
    }
</style>