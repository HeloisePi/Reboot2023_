<script>
    
</script>
<header>
    <img src="/favicon.svg" alt="logo home">   
    <div class="link">
        <a href="#"><p>Loisirs</p></a>
        <a href="#"><p>Se nourrir</p></a>
        <a href="#"><p>Vêtements</p></a>
    </div>
</header>
<div class="blur"></div>
<div class="blur white"></div>
<div class="behind"></div>

<style>
    header{
        display: flex;
        z-index: 10;
        height: 70px;
        justify-content: space-between;
        padding: 1rem;
        align-items: center;
        position: fixed;
        top: 0;
        width: 100vw;
    }
    .link{
        display: flex;
        gap: 1rem;
    }
    img{
        width: 4rem;
    }
    .blur{
        width: 100vw;
        height: 70px;
        -webkit-filter: blur(5px);
        -moz-filter: blur(5px);
        -o-filter: blur(5px);
        -ms-filter: blur(5px);
        filter: blur(5px);
        backdrop-filter: blur(5px);
        position: fixed;
        border-radius: 5px;
        z-index: 5;
        top: 0;
    }
    .white{
        background-color: white;
        opacity: 10%;
    }
    .behind{
        width: 100vw;
        height: 70px;
        position: sticky;
        z-index: 4;
        top: 0;
    }
</style>