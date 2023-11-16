<script>
    import Contenaire from "../component/Contenaire.svelte";
    import HeroTheme from "../component/HeroTheme.svelte";
	import Suggestion from "../component/Suggestion.svelte";
    import ThemeButton from "../component/ThemeButton.svelte";
    import TitleH2 from "../component/TitleH2.svelte";
</script>


<HeroTheme srcImg="/images/logo/clothes.svg" title="Se vêtir "></HeroTheme>
<section>
    <Contenaire><p>Ce n’est pas secret, l’industrie du textile est très gourmande en énergie et a
         un gros impact environnemental. <span class="green">Dans un esprit de décroissance, tu peux favoriser des 
         vêtements de qualité et ne pas céder à la sur-consommation.</span> Mais voilà, s’habiller de manière 
         responsable n’est pas chose aisée pour un petit budget. <span class="bold">Retrouve nos astuces écologiques et 
         adaptées à ton porte-monnaie.</span></p></Contenaire>
    <div class="">

        <TitleH2>Nos Articles</TitleH2>
        <div class="allButton">
            
            <ThemeButton src="../sevetir/retouches" logo="/images/logo/scisor.svg">Retoucher ses vêtements</ThemeButton>
            <ThemeButton  src="../sevetir/seconde-main" logo="/images/logo/eco.svg">L’esprit “Seconde main”</ThemeButton>
        </div>
    </div>
    
    <Suggestion src="#" srcImg="/images/suggestions/3.png" title="NRV : des pépites de toute l’Europe">Une chose ressort lorsqu’on rentre chez Steak Fripes : la gentillesse et la bienveillance de ses propriétaires, qui vous aiderons à dénicher la perle rare. 
        Il y a de tout : costumes d’époque, accessoires en folies… Quoi que vous cherchiez, vous le trouverez au 62 Rue du Mirail, 33800 Bordeaux !</Suggestion>

        <Suggestion src="#" srcImg="/images/suggestions/3.png" title="Steak Fripes : la friperie pour toutes les envies">Une chose ressort lorsqu’on rentre chez Steak Fripes : la gentillesse et la bienveillance de ses propriétaires, qui vous aiderons à dénicher la perle rare cachée rien que pour vous dans leur boutique. Par chez Steak Fripes, il y a de tout, mais alors vraiment de tout : costumes d’époque, robes des années 20 à 60, accessoires en folies… Quoi que vous cherchiez, vous le trouverez !</Suggestion>
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
    }
    @media screen and (max-width: 880px) {
        section .allButton{
            flex-direction: column;
            justify-content: center;
            align-items: center;
    }
    }
</style>