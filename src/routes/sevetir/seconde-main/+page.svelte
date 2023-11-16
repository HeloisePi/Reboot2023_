<script>
    import Contenaire from "../../component/Contenaire.svelte";
    import HeroTheme from "../../component/HeroTheme.svelte";
    import ThemeButton from "../../component/ThemeButton.svelte";
    import TitleH2 from "../../component/TitleH2.svelte";
</script>

<HeroTheme srcImg="/images/logo/eco.svg" title="La seconde 
Main"></HeroTheme>
<section>
<Contenaire><p>Les objets, les vêtements, les meubles, les appareils multimédias, l’électroménager, tout cela a un prix et pas des moindre. Alors comment limiter les frais pour la planète et pour toi ? La seconde main est la solution.<br><br>

    Que ce soit de l’occasion ou du reconditionné, tu peux faire de belles économies et éviter de surconsommer grâce à cela. Mais à part Vinted et Leboncoin, où aller chiner ? <br><br>
<li>Les offres sur Internet : il existe bon nombre de sites pour acheter du reconditionné ce qui est déjà économique, mais pour rentabiliser au maximum, tu peux consulter les offres flash sur le reconditionné qui te feront encore plu économiser, pour plus d’info tu peux checker ce lien: https://www.reepeat.fr/articles/top-15-des-meilleurs-sites-de-produits-reconditionnes-en-2021</li>
<li>Tu peux aussi te rendre dans dépôts vente et des friperies, le tout c’est de trouver les moins cher et de bien chiner, on te laisse regarder ici : https://bordeauxsecret.com/les-meilleures-friperies-de-bordeaux/</li>
<li>Emmaüs est une super alternative, tu peux trouver des meubles et des vêtements pas cher, on te laisse lien pour en savoir plus : https://emmaus-france.org/groupe/emmaus-gironde/</li>
<li>Il existe un site, Geev, les gens donnent des objets prêt de chez toi, car ils n'en veulent juste plus, profites-en : https://www.geev.com/fr</li>
<li>Et pour ne pas souffrir de fracture numérique, on te recommande Emmaüs connect qui propose de l’aide au personne en précarité et qui n’ont pas les moyens d’acheter du matériels multimédia : https://emmaus-connect.org/bordeaux/
</li>
</p>
    
    </Contenaire>
    <div class="">

        <TitleH2>Un autre article susceptible de vous intéresser</TitleH2>
        <div class="allButton">
            
            <ThemeButton src="../sevetir/retouches" logo="/images/logo/scisor.svg">Retoucher ses vêtements :<br><br>
                Lieux et Tutos</ThemeButton>
        </div>
    </div>

</section>


<style>
    section{
        width: 100vw;
        padding-left: 5rem;
        padding-right: 5rem; 
    }
    @media screen and (max-width: 450px) {
        section{
        padding-left: 1rem;
        padding-right: 1rem;
    }
    }
    p{
        max-width: 900px;
    }
    div{
        margin-bottom: 5rem;
    }
</style>