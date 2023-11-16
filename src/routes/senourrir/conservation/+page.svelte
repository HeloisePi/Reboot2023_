<script>
    import Contenaire from "../../component/Contenaire.svelte";
    import HeroTheme from "../../component/HeroTheme.svelte";
</script>

<HeroTheme srcImg="/images/logo/foodContainer.svg" title="Comment bien 
conserver ses 
aliments"></HeroTheme>
<section>
<Contenaire><p>Parlons peu, parlons bien, parlons stockage alimentaire.


 Pour éviter que tes courses ne se périment, faut devenir un pro du stockage. 
Mets-toi dans le mood du frigo bien organisé, des sachets hermétiques et des boîtes étanches. 
   <span class="green">La fraîcheur, c'est ton nouveau mantra.</span>
    
Les légumes et les fruits sont les plus compliqués, mais une fois que tu maîtrises l’art de la conservation,
     tu peux garder ton concombre et tes tomates fraîches plus longtemps que tu ne le pensais.
Ah, et parlons des restes. Ne les laisse pas moisir dans le coin du frigo. 
    Mets-les dans des récipients sympas, joue au Tetris dans ton congélo, et laisse la magie 
    de la conservation opérer.
Pour en savoir plus, <a href="https://cuisine-addict.com/comment-bien-conserver-ses-aliments-au-refrigerateur/">clique ici</a>.</p>

    
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

    a {
        color: #21864F;
    }

    a:hover {
        text-decoration: underline;
        font-weight: bold;
        text-underline-offset: 0.3rem;
    }
</style>