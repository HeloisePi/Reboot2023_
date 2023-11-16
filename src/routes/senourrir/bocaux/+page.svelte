<script>
    import Contenaire from "../../component/Contenaire.svelte";
    import HeroTheme from "../../component/HeroTheme.svelte";
</script>

<HeroTheme srcImg="/images/logo/jar.svg" title="Comment faire des 
bocaux"></HeroTheme>
<section>
<Contenaire><p>Est-ce que tu connais la magie des bocaux ? </p>
    <p>C'est comme une capsule temporelle pour tes victuailles.</p>
    <p><span class="green">Pas de soucis, mets-les dans un bocal!</span> C'est pas juste stylé dans le frigo, 
    c'est une manière de dire "Je ne gaspille rien."</p>
    
    
    <p>Alors, la prochaine fois que tu fais une énorme marmite de ragoût ou que t'as des 
    fraises à revendre, <span class="green">prends tes bocaux, joue au chef cuistot, et sauve le monde, 
    une conserve à la fois.</span> C'est pas juste une astuce de grand-mère.</p>
    
    <p>Pour découvrir pleins d'astuces, 
        <a href="​https://www.adeline-cuisine.fr/comment-faire-des-conserves-et-bocaux-maison-astuces-et-conseils/">clique ici</a> !</p>
    ​
    
    </p>
    
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