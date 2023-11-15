<script>
    export let title;
</script>

<h1> {title}</h1>
<img src="/images/mainImg.png" alt="Main">
<div class="blur"></div>
<div class="white blur"></div>

<style>
    .blur{
        transform: translate(-50%, -45vw);
        margin-left:50% ;
        width: 70vw;
        height: 35vw;
        -webkit-filter: blur(5px);
        -moz-filter: blur(5px);
        -o-filter: blur(5px);
        -ms-filter: blur(5px);
        filter: blur(5px);
        backdrop-filter: blur(5px);
        position: absolute;
        border-radius: 5px;
    }
    .white{
        background-color: white;
        opacity: 10%;
    }
    img{
        width: 100vw;
    }
    h1{
        position: absolute;
    z-index: 2;
    margin-left: 50%;
    transform: translate(-50%, 24vw);
    color: white;


    }

</style>