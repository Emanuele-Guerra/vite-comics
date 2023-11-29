<script>

</script>


<template>
    <section>
     <div class="flag-wrapper">
            <div>
            <div class="sign-up">
                <p>SIGN-UP NOW!</p>
            </div>
        </div>
        <div>
            <div class="icon-wrap">
                <p>FOLLOW US</p>
                <img src="img/footer-facebook.png" alt="">
                <img src="img/footer-twitter.png" alt="">
                <img src="img/footer-youtube.png" alt="">
                <img src="img/footer-pinterest.png" alt="">
                <img src="img/footer-periscope.png" alt="">
            </div>
        </div>
     </div>
       
    </section>
</template>


<style scoped>
    section{
        width: 100%;
        height: 100px;
        background-color: #212121;
        z-index: 1;
        
    }
    .flag-wrapper{
        margin: 0 auto;
        width: 80%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 100%;
    }
    .icon-wrap{
        display: flex;
        align-items: center;
        color: #0C7CEC;
        font-weight: 700;
    }
    .icon-wrap p{
        margin-right: 0.5rem;
    }
    img{
        margin: 0.5rem;
        width: 1.5rem;
    }
    .sign-up{
        padding: 0.5rem;
        color: white;
        border: 3px solid #0C7CEC;
    }
</style>