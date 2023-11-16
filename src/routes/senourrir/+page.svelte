<script>
    import Contenaire from "../component/Contenaire.svelte";
    import HeroTheme from "../component/HeroTheme.svelte";
    import ThemeButton from "../component/ThemeButton.svelte";
    import TitleH2 from "../component/TitleH2.svelte";
</script>


<HeroTheme srcImg="/images/logo/food.svg" title="Se nourrir"></HeroTheme>
<section>
    <Contenaire><p>À l'heure où la surconsommation aggrave les défis environnementaux, il est crucial d'explorer des voies alternatives pour nourrir notre corps et notre planète de manière plus durable. Cette plateforme est votre guide pour comprendre l'importance de la décroissance et de la réduction de consommation dans le domaine alimentaire.À l'heure où la surconsommation aggrave les défis environnementaux, il est crucial d'explorer des voies alternatives pour nourrir notre corps et notre planète de manière plus durable. Cette plateforme est votre guide pour comprendre l'importance de la décroissance et de la réduction de consommation dans le domaine alimentaire.</p></Contenaire>
    <div class="">

        <TitleH2>Nos Articles</TitleH2>
        <div class="allButton">
            
            <ThemeButton src="../senourrir/conservation" logo="/images/logo/foodContainer.svg">Comment bien conserver ses aliments</ThemeButton>
            <ThemeButton  src="../senourrir/bien-manger" logo="/images/logo/food.svg">Se nourrir à faible impact et moindre frais</ThemeButton>
            <ThemeButton  src="../senourrir/congelation" logo="/images/logo/cold.svg">Règles de congélation</ThemeButton>
            <ThemeButton  src="../senourrir/bocaux" logo="/images/logo/jar.svg">Comment faire des bocaux</ThemeButton>
        </div>
    </div>

</section>


<style>
        section{
        width: 100vw;
        padding-left: 5rem;
        padding-right: 5rem; 
        display: flex;
        flex-direction: column;
        gap: 5rem;
        padding-bottom: 5rem;
    }
    @media screen and (max-width: 450px) {
        section{
        padding-left: 1rem;
        padding-right: 1rem;
    }
    }
    h2{
        margin-bottom: 2rem;
    }
    li{
        margin-bottom: 0.5rem;
    }
    .allButton{
        display: flex;
        gap: 2rem;
    }
</style>