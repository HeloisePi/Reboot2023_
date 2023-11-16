<script>
    import Contenaire from "../../component/Contenaire.svelte";
    import HeroTheme from "../../component/HeroTheme.svelte";
</script>

<HeroTheme srcImg="/images/logo/cold.svg" title="Règles de 
congélation"></HeroTheme>
<section>
<Contenaire><p>T'as déjà pensé <span class="green">à la congélation comme super-pouvoir contre le gaspi?</span> Ça vaut le coup de creuser 
    cette idée. </p>
    <p>Des restes de pizza ou un surplus de lasagnes? Pas de panique, 
    congèle-les! C'est pas juste pratique, c'est aussi un geste de guerre 
    contre le gâchis alimentaire. C'est cool, économique, et ça donne une 
    deuxième chance à tes repas.</p>
    
    
    <p>Alors, la prochaine fois que t'as trop cuisiné ou que tu sens que tes 
    fraises vont rendre l'âme, ouvre grand la porte du frigo, prépare tes sacs de 
    congélation, et fais un dab pour dire adieu au gaspi.</p>
    <p>Mais attention cela ne se fait pas n’importe comment, pour être sûr 
    que ta nourriture est safe !</p>

    <p>Pour en savoir plus, 
        <a href="https://www.albal.fr/fr/les-10-regles-dor-pour-bien-congeler-et-decongeler-ses-aliments-612.html">clique ici</a> !</p>
    
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

    a {
		color: #21864f;
		font-weight: bold;
	}

	a:hover {
		text-decoration: underline;
		text-underline-offset: 0.4vh; 
	}

</style>