<script>
   export default{
    name: "headApp",
    data (){
        return{
            navLinks: [
                 {
                    name: "CHARACTERS",
                    url: "#"
                },
                 {
                    name: "COMICS",
                    url: "#"
                },
                 {
                    name: "MOVIES",
                    url: "#"
                },
                 {
                    name: "TV",
                    url: "#"
                },
                 {
                    name: "GAMES",
                    url: "#"
                },
                 {
                    name: "COLLECTIBLES",
                    url: "#"
                },
                 {
                    name: "VIDEOS",
                    url: "#"
                },
                 {
                    name: "FANS",
                    url: "#"
                },
                 {
                    name: "NEWS",
                    url: "#"
                },
                 {
                    name: "SHOP",
                    url: "#"
                },

            ]
        }
    },
   }
</script>

<template>
    <div>
        <nav>
            <div>
                <img src="img/dc-logo.png" alt="">
            </div>
            <div>
                <a v-for="i in navLinks" href="">{{ i.name }}</a>
            </div>
        </nav>
    </div>
</template>

<style scoped>
    a{
        margin: 0 1rem;
        text-decoration: none;
        font-size: 12px;
        font-weight: 700;
        color: black;
        height: 80px;
        
        padding-bottom: 25px;
    }
    a:hover{
        border-bottom: 5px solid #0C7CEC;
    }
    nav{
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 80%;
        height: 80px;
        margin: 0 auto;
    }
    img{
        width: 60px;
    }
</style>