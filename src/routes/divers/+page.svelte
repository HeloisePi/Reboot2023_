<script>
    import Contenaire from "../component/Contenaire.svelte";
    import HeroTheme from "../component/HeroTheme.svelte";
    import ThemeButton from "../component/ThemeButton.svelte";
    import TitleH2 from "../component/TitleH2.svelte";
</script>


<HeroTheme srcImg="/images/logo/eco.svg" title="Divers"></HeroTheme>
<section>
    <Contenaire><p>D’après le site notre-environnement.gouv.fr :  <span class="green">“En 2019, les véhicules 
        particuliers émettent 71,6 millions de tonnes équivalent CO2”.</span> C’est pourquoi se déplacer proprement est un 
        enjeu essentiel, de plus, cela permet de faire des économies.
        En 2020, le réseau de tramway de Bordeaux est positionné en tête des réseaux des grandes villes. 
        Toutefois, <span class="green">il faut garder en tête que le tram n’est pas la seule alternative.</span> </p></Contenaire>
        <div class="link">
            
            <a href="https://boutique.infotbm.com/products/34 " class="help">
                TBM englobe, en plus du tramway, le vélo électrique, le bus et bien d’autres services. Dans cette démarche, le service propose des tarifs préférentiels pour les étudiants, tu peux les retrouver ici. 
            </a>
            <a href="https://www.infotbm.com/fr/tarificationsolidaire" class="help">
                Il existe des remise pour les personnes en situation de précarité, pour en savoir plus, c’est ici !
            </a>
            <a href="https://www.economie.gouv.fr/particuliers/tout-savoir-covoiturage" class="help">
                Le covoiturage est une solution intelligente pour des trajets quotidiens réguliers ou des trajets plus, tu peux te renseigner ici !
            </a>
            <a href="https://www.sncf-connect.com/app/catalogue/description/carte-avantage-jeune" class="help">
                Avec la SNCF, des tarifs réduits sont proposés aux étudiants et il est possible d’acheter une carte avantage jeune pour profiter de réduction toute l’année. Pour en savoir plus clique ici !
            </a>
            <a href="https://www.unairdebordeaux.fr/article/trottinettes-electriques-a-bordeaux/" class="help">
                Pour la trottinette électrique et les vélos, tu en sauras plus ici ! 
            </a>
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
    li{
        margin-bottom: 0.5rem;
    }
    .help{
        max-width: 500px;
        max-height: 300px;
        border-radius: 50px;
        border-radius: 10px;
        background: #ffffff;
        box-shadow:  20px 20px 60px #d9d9d9,
                    -20px -20px 60px #ffffff;
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 2rem;
        transition: ease 500ms;
    }
    .help:hover{
        transform: scale(110%);
    }
    .link{
        display: grid;
        grid-template-columns: 1fr 1fr;
        justify-items: center;
        align-items: center;
        row-gap: 2rem;
    }
    @media screen and (max-width: 1200px) {
    .link{      
        grid-template-columns: 1fr;
    }
}
</style>