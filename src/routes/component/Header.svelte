<script>
    
</script>
<header>
    <a href="../../"><img src="/favicon.svg" alt="logo home"></a>
    <div class="link">
        <a href="../sedivertir"><p>Se divertir</p></a>
        <a href="../sevetir"><p>Se vêtir</p></a>
        <a href="../senourrir"><p>Se nourrir</p></a>
        <a href="../divers"><p>Divers</p></a>
        <a href="../qui-sommes-nous"><p>Qui sommes nous ?</p></a>
    </div>
</header>

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
    .behind{
        width: 100vw;
        height: 70px;
        position: sticky;
        z-index: 4;
        top: 0;
    }
</style>