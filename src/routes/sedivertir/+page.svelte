<script>
	import Contenaire from "../component/Contenaire.svelte";
    import HeroTheme from "../component/HeroTheme.svelte";
	import Suggestion from "../component/Suggestion.svelte";
	import ThemeButton from "../component/ThemeButton.svelte";
    import TitleH2 from "../component/TitleH2.svelte";

</script>


<HeroTheme srcImg="/images/logo/hobbies.svg" title="Se divertir"></HeroTheme>
<section>
    <Contenaire>
        <h2 class="bold"> Découvrez l'Excitation de Novembre avec la Carte Jeune à Bordeaux !</h2>
        <p>
            <li>Ciné Petit’Déj – Mon Voisin TotoroCinéma La LanterneDimanche 19 novembre, 10h00Cinéma - Projection</li>
            <li>Les Veilleurs de NuitMusée Mer MarineVendredi 17 novembre, 19h00Exposition</li>
            <li>Kapwani Kiwanga, RetenueCapc Musée d'art contemporain de Bordeaux30 juin 2023 - 7 janvier 2024Exposition</li>
            <li>Visite dans le noirGalerie des Beaux-Arts BordeauxMercredi 22 novembre, 15h30Visite - Balade</li>
            <li>Benjamin EppsRocher de PalmerVendredi 24 novembre, 20h30Concert</li>
            <li>HervéLe KrakatoaSamedi 18 novembre, 20h30Concert</li>
        </p>
    </Contenaire>

    <Suggestion srcImg="/images/sugestion/4.png" title="Ciné Petit’Déj – Mon Voisin Totoro" >Séance précédée d’un petit déjeuner offert, en partenariat avec la boulangerie Maison Valé. Replongez dans le classique de Miyazaki avant de découvrir à La Lanterne son nouveau film.</Suggestion>
    <Suggestion srcImg="/images/sugestion/5.png" title="Les Veilleurs de Nuit" >Un court-métrage de Christophe Brachet et des oeuvres de Richard Giacobetti seront le point de départ d'un échange poétique entre les deux artistes et la journaliste et animatrice Sabine Quindou.</Suggestion>
    <div class="">

        <TitleH2>Nos Articles</TitleH2>
        <div class="allButton">
            
            <ThemeButton src="../sedivertir/boireunverre" logo="/images/logo/cocktail.svg">Schlouk map, pour boire des verres sans se ruiner !</ThemeButton>
            <ThemeButton  src="../sedivertir/eturecup" logo="/images/logo/light.svg">Étu’Ré quoi ?</ThemeButton>
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