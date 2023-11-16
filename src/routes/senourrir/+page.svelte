<script>
    import Contenaire from "../component/Contenaire.svelte";
    import HeroTheme from "../component/HeroTheme.svelte";
	import Suggestion from "../component/Suggestion.svelte";
    import ThemeButton from "../component/ThemeButton.svelte";
    import TitleH2 from "../component/TitleH2.svelte";
</script>


<HeroTheme srcImg="/images/logo/food.svg" title="Se nourrir"></HeroTheme>
<section>
    <Contenaire><p>À l'heure où la surconsommation aggrave les défis environnementaux, 
        il est crucial <span class="green">d'explorer des voies alternatives pour nourrir notre corps et notre planète de manière 
        plus durable</span>. Cette plateforme est votre guide pour comprendre l'importance de la décroissance et de 
        la réduction de consommation dans le domaine alimentaire.
        </p></Contenaire>
    <div class="">

        <TitleH2>Nos Articles</TitleH2>
        <div class="allButton">
            
            <ThemeButton src="../senourrir/conservation" logo="/images/logo/foodContainer.svg">Comment bien conserver ses aliments</ThemeButton>
            <ThemeButton  src="../senourrir/bien-manger" logo="/images/logo/food.svg">Se nourrir à faible impact et moindre frais</ThemeButton>
            <ThemeButton  src="../senourrir/congelation" logo="/images/logo/cold.svg">Règles de congélation</ThemeButton>
            <ThemeButton  src="../senourrir/bocaux" logo="/images/logo/jar.svg">Comment faire des bocaux</ThemeButton>
        </div>
    </div>

    <Suggestion src="https://www.instagram.com/p/BcVkbHeHz9d/?utm_source=ig_embed&ig_rid=703d78e0-90d7-4e57-88b2-34c15b0a8673" srcImg="/images/suggestions/5.png" title="Pizzeria Filippo | Pizzeria Filippo 11 Rue Beyssac">Situé dans le quartier des Capucins, cet italien n'a plus sa réputation à faire. Beaucoup disent qu'il s'agit des pizzas les plus généreuses de la ville. Nous on les adore ! Coup de cœur pour ces créations italiennes traditionnelles et soignées dans une salle cosy aux murs paprika et aux accents de pierre.</Suggestion>
    <Suggestion src="https://www.instagram.com/p/BcVkbHeHz9d/?utm_source=ig_embed&ig_rid=703d78e0-90d7-4e57-88b2-34c15b0a8673" srcImg="/images/suggestions/6.png" title="Wok Way | Pizzeria Filippo 12 Rue Paul Louis Lande">Wok Way, du côté de la Grosse Cloche. Concoctés avec passion, et uniquement des produits triés sur le volet, le restaurant est un des meilleurs rapports qualité-prix pour toucher aux spécialités culinaires d'Asie. De la Chine, au Vietnam, en passant par la Corée ou la Thaïlande.</Suggestion>
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
    .allButton{
        display: flex;
        gap: 2rem;
        flex-wrap: wrap;
        justify-content: center;
            align-items: center;
    }
    @media screen and (max-width: 880px) {
        section .allButton{
            flex-direction: column;
            justify-content: center;
            align-items: center;
    }
    }
</style>