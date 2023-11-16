<script>
    import Contenaire from "../../component/Contenaire.svelte";
    import HeroTheme from "../../component/HeroTheme.svelte";
</script>

<HeroTheme srcImg="/images/logo/light.svg" title="Étu’Ré quoi ?"></HeroTheme>
<section>
<Contenaire><p>Étu’Récup. <br>

    <p>C’est une association bordelaise présente sur le Campus Universitaire de Bordeaux, 
    Pessac, Talence et Gradignan. Elle réunit plus de 3 000 membres et <span class="green">propose des activités 
    pour créer ses propres vêtements, réparer ses objets ou fabriquer ses produits ménagers</span> en respectant la planète. </p>
    
   <p>En bref, Étu’Récup, c’est tout simplement partager des valeurs comme l’entraide, 
    la lutte contre la précarité et l’isolement social, le respect de la planète et des autres. 
    En plus de ça, il y a des événements plutôt sympas. </p> 
    
    <p>Par exemple, vendredi 24 novembre (je sais, c’est bientôt), les bénévoles 
    organisent une soirée avec buffet, blind test, quiz, jeux de kermesse… le tout dans une démarche éco-responsable et anti-gaspi. 
    Par exemple, les jeux de kermesse, ils sont fabriqués qu’avec du matériel de récup’. <br>
    C’est ouvert à tous et l’entrée est gratuite.</p>
    
    <p>Le point positif, <span class="green">c’est qu’en devenant membre d’une association, ça te permet de 
    rejoindre une communauté</span>. Tu rencontres des gens, tu participes à des activités variées 
    et du coup, tu t’ouvres à des choses auxquelles tu n’aurais peut-être jamais pensées ! </p>
    
    <p>Je te laisse le lien de leur site <a href="http://eturecup.org">juste ici </a>;)</p>
    
    </Contenaire>
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
        margin-bottom: 3vh;
    }
</style>