<script>
	import Hero from "./component/Hero.svelte";
    import TitleH2 from "./component/TitleH2.svelte";
    import Theme from "./component/Theme.svelte";
	import Suggestion from "./component/Suggestion.svelte";
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>


<Hero title="Frynge"/>
<section>
    <p class="textDescription">Bienvenue sur Frynge, la plateforme <span class="bold"> bons plans bordelais </span> qui t’aide à entrer dans une démarche de <span class="bold"> décroissance</span>. Tutos, activités, astuces, bons plans… fais le plein d’idées à petit budget.</p>
    <TitleH2>Bons plans</TitleH2>
    <div class="BoutonsTheme">
        <Theme src="../sedivertir" logo="/images/logo/hobbies.svg" > Se<br> Divertir</Theme>
        <Theme src="../sevetir" logo="/images/logo/clothes.svg" >Se<br> vêtir</Theme>
        <Theme src="../senourrir" logo="/images/logo/food.svg" >Se<br> nourrir</Theme>
        <Theme src="../divers" logo="/images/logo/divers.svg" >Divers</Theme>
    </div>
    <TitleH2>Nos vidéos</TitleH2>
    <div class="videos">
        <iframe src="https://youtube.com/embed/B4F4y73JQh4?si=22ig2V9KQgsZZ079" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        <!--<iframe src="https://youtube.com/embed/HnD_0sSsEas?si=7bNNWkt6cDfzNv0O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        <iframe src="https://youtube.com/embed/_UhNp9cU87o?si=uc8Ly51gTilccDqf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>-->
    </div>
    <TitleH2>Suggestions</TitleH2>
    <div class="allSuggestion">
        <Suggestion src="../sevetir/retouches" srcImg="/images/logo/scisor.svg" title="Retoucher ses vêtements : Lieux et Tutos">Plutôt que de balancer tes fringues, pourquoi pas les réparer ?
            On sait tous que la mode va plus vite que la lumière, mais au lieu de suivre le rythme, pourquoi ne pas ralentir et donner une seconde vie à ton jean préféré? Un coup de couture par-ci, un remplacement de bouton par-là, et bam le tour est joué.</Suggestion>
        <Suggestion src="../senourrir/conservation" srcImg="/images/logo/foodContainer.svg" title="Comment bien conserver ses aliments">Pour éviter que tes courses ne se périment, faut devenir un pro du stockage. 
            Mets-toi dans le mood du frigo bien organisé, des sachets hermétiques et des boîtes étanches. La fraîcheur, c'est ton nouveau mantra.</Suggestion>
        <Suggestion src="../sedivertir/eturecup"  srcImg="/images/logo/light.svg" title="Étu’Ré quoi ?">C’est une association bordelaise présente sur le Campus Universitaire de Bordeaux, Pessac, Talence et Gradignan. Elle réunit plus de 3 000 membres et propose des activités pour créer ses propres vêtements, réparer ses objets ou fabriquer ses produits ménagers en respectant la planète.</Suggestion>
    </div>

</section>

<style>
    
    .textDescription{
        margin: 0 auto;
        margin-bottom: 5rem;
        margin-top: 5rem;
        width: 80%;
        max-width: 800px;
    }
    .videos{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        justify-items: center;
        padding-bottom: 5rem;
    }

    @media screen and (max-width: 1250px) {
        .videos{
            grid-template-columns: 1fr 1fr;
            row-gap: 2rem;
        }
    }
    @media screen and (max-width: 922px) {
        .videos{
            grid-template-columns: 1fr;
        }
        section .BoutonsTheme{
            grid-template-columns: 1fr 1fr;
        }
    }
    @media screen and (max-width: 520px) {
        .videos iframe{
            width: 170px;
            height: 300px;
        }
    }

    iframe{
        border-radius: 10px;
        width: 270px;
        height: 500px;
    }
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
    .BoutonsTheme{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        justify-items: center;

        padding-bottom: 5rem;
        margin-left: 50%;
        transform: translateX(-50%);
        width: 100vw;
    }
    @media screen and (max-width: 1180px) {
        .BoutonsTheme{
        grid-template-columns: 1fr 1fr 1fr;
        row-gap: 1rem;
        }
    }
    @media screen and (max-width: 606px) {
        section .BoutonsTheme{
            grid-template-columns: 1fr;
            row-gap: 1rem;
        }
    }
    @media screen and (max-width: 950px) {
        section .allSuggestion{
            display: grid;
            grid-template-columns: 1fr 1fr;
            justify-items: center;
            gap: 1rem;
        }
        section .allSuggestion{
            display: grid;
            grid-template-columns: 1fr;
            justify-items: center;
            gap: 1rem;
        }
    }
    @media screen and (max-width: 770px) {
        section .allSuggestion{
            display: grid;
            grid-template-columns: 1fr;
            justify-items: center;
            gap: 1rem;
        }
    }
    .allSuggestion{
            display: flex;
            flex-direction: column;
            gap: 3rem;
            margin-bottom: 5rem;
        }





</style>