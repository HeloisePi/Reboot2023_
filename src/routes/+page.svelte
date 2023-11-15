<script>
	import Hero from "./component/Hero.svelte";
    import TitleH2 from "./component/TitleH2.svelte";
    import Theme from "./component/Theme.svelte";
	import Suggestion from "./component/Suggestion.svelte";
</script>
<Hero title="Frynge"/>
<section>
    <p class="textDescription">Bienvenue sur Frynge, la plateforme <span class="bold"> bons plans </span> qui t’aide à entrer dans une démarche de <span class="bold"> décroissance</span>. Tutos, activités, astuces, bons plans… fais le plein d’idées à petit budget.</p>
    <TitleH2>Bons plans</TitleH2>
    <div class="BoutonsTheme">
        <Theme src="../sedidivertir" logo="/images/logo/hobbies.svg" > Se<br> Divertir</Theme>
        <Theme src="../sedivertir" logo="/images/logo/clothes.svg" >Se<br> vêtir</Theme>
        <Theme src="../senourrir" logo="/images/logo/food.svg" >Se<br> nourrir</Theme>
        <Theme src="../divers" logo="/images/logo/divers.svg" >Divers</Theme>
    </div>
    <TitleH2>Nos vidéos</TitleH2>
    <div class="videos">
        <iframe src="https://youtube.com/embed/fTdFc_MfD7Y?si=3RqXL7fAtPuf3lV5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
       <iframe src="https://youtube.com/embed/HnD_0sSsEas?si=7bNNWkt6cDfzNv0O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        <iframe src="https://youtube.com/embed/_UhNp9cU87o?si=uc8Ly51gTilccDqf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
    <TitleH2>Suggestion</TitleH2>
    <div class="allSuggestion">
        <Suggestion srcImg="/images/sugestion/1.webp" title="Izïa">Depuis la sortie de son cinquième album La vitesse, Izïa la rockeuse au cœur tendre, multiplie les dates telle une tornade et se donne corps et âme à son public.</Suggestion>
        <Suggestion srcImg="/images/sugestion/2.webp" title="Boutique éphémère vintage">Nouveau rendez-vous du marché des Causettes avec des friperies de dingue, dans le lieu atypique du théâtre de la Rousselle!<br>
            Sam. 18 nov. 2023 11:00 - dim. 19 nov. 2023 19:00 CET<br>
            77 Rue de la Rousselle 33000 Bordeaux</Suggestion>
        <Suggestion srcImg="/images/sugestion/3.webp" title="Afterwork Vins du Beaujolais">Nous proposons deux sessions par afterwork, la première à 18h30 et la seconde à 20h30, afin de correspondre au mieux à vos agendas.<br>
            Animé par : Cécile Bossan-Redon <br>
            En partenariat avec : Inter Beaujolais <br></Suggestion>
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