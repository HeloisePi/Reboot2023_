<script>
    
</script>
<header>
    <a href="../../"><img src="/favicon.svg" alt="logo home"></a>
    <div class="link">
        <a href="../sedivertir"><p>Se divertir</p></a>
        <a href="#"><p>Se vêtir</p></a>
        <a href="../senourrir"><p>Se nourir</p></a>
        <a href="#"><p>Divers</p></a>
        <a href="#"><p>À propos</p></a>
        <a class ="addTuto" href="#"><p>Ajouter un tuto</p></a>
    </div>
</header>
<!-- <div class="blur"></div> -->
<!-- <div class="blur white"></div> -->
<div class="behind"></div>

<style>

    .addTuto{
        background-color: #21864F;
        padding: 5px;
        padding-left: 10px;
        padding-right: 10px;
        border-radius: 10px;
        color: white;
    }
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
        background-color: white;
        
            box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
            backdrop-filter: blur(5.5px);
    }
    .link{
        display: flex;
        gap: 1.5rem;
        align-items: center;
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