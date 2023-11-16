<script>
    import Contenaire from "../../component/Contenaire.svelte";
import HeroTheme from "../../component/HeroTheme.svelte";
</script>

<HeroTheme srcImg="/images/logo/cocktail.svg" title="Schlouk map, pour boire des verres sans se ruiner !"></HeroTheme>
<section>
<Contenaire><p>Est-ce que toi aussi t’aimes aller boire des verres avec tes potes, mais tu vas toujours dans le même bar parce que soit la pinte n'est pas chère, soit la terrasse est grande, soit tu ne connais pas les autres bars ? <br>
 
    J’ai une solution pour toi : la Schlouk map. C’est une application gratuite qui répertorie tous les bars de ta ville en indiquant leurs tarifs, et même les horaires d’Happy Hour.<br>
    
    On le sait tous, boire des coups, c’est sympa, mais ça coûte ! Là, tu pourras trouver les meilleurs tarifs pour profiter sans te ruiner. <br>
    
    L’appli est super pratique, les bars partenaires sont répertoriés sur une carte ce qui te permet de les retrouver rapidement. Tu peux même filtrer tes recherches selon ce que tu veux : les Happy hours, la meilleure terrasse, une pinte à moins de 4€… <br> 
    Et quand tu trouves des vrais bons plans, tu peux les ajouter à tes favoris ou les retrouver dans tes bars visités.<br>
    
    Ce n'est pas trop pratique ? Ça te permet de découvrir de nouveaux endroits sans mauvaises surprises (parce que les bars cools où tu te retrouves à payer une blinde, on n’aime pas).<br>
    
    Bref, je te laisse profiter (toujours avec modération, je suis obligée de te le dire) et pour télécharger l’appli,<a href="c’est par là">c’est par là</a> , ou sinon tu peux la retrouver directement depuis Play store ou App store !<br></p>
    
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
    }
</style>