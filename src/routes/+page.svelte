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
        <Suggestion srcImg="/images/sugestion/1.png" title="Izïa">Depuis la sortie de son cinquième album La vitesse, Izïa la rockeuse au cœur tendre, multiplie les dates telle une tornade et se donne corps et âme à son public.</Suggestion>
        <Suggestion srcImg="/images/sugestion/2.png" title="Boutique éphémère vintage">Nouveau rendez-vous du marché des Causettes avec des friperies de dingue, dans le lieu atypique du théâtre de la Rousselle!<br>
            Sam. 18 nov. 2023 11:00 - dim. 19 nov. 2023 19:00 CET<br>
            77 Rue de la Rousselle 33000 Bordeaux</Suggestion>
        <Suggestion srcImg="/images/sugestion/3.png" title="Afterwork Vins du Beaujolais">Nous proposons deux sessions par afterwork, la première à 18h30 et la seconde à 20h30, afin de correspondre au mieux à vos agendas.<br>
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





/*    reset.css */

*{
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
}

/* HTML5 display-role reset for older browsers */

article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
    display: block;
}


ol,
ul {
    list-style: none;
}

blockquote,
q {
    quotes: none;
}




table {
    border-collapse: collapse;
    border-spacing: 0;
}
a{
    text-decoration: none;
}
* {
    box-sizing: border-box;
}

html, body{
    width: 100vw;
    overflow-x: hidden;
    scroll-behavior: smooth;
}

/* width */
::-webkit-scrollbar {
    width: 5px;
    height: 5px;
  }
  
  /* Track */
  ::-webkit-scrollbar-track {
    background: #f1f1f1; 
  }
   
  /* Handle */
  ::-webkit-scrollbar-thumb {
    background: #888; 
  }
  
  /* Handle on hover */
  ::-webkit-scrollbar-thumb:hover {
    background: #555; 
  }

img{
    width: fit-content;
    height: fit-content;
}


	/*   Variable.css */
@font-face {
    font-family: 'HelveticaNeueInterface';
    src: url(/src/lib/assets/HelveticaNeueInterface.ttf);
}
@font-face {
    font-family: 'HelveticaNeueInterface_thin';
    src: url(/src/lib/assets/HelveticaNeueInterface_thin.ttf);
}

h1{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New'; 
    font-size: 4rem;
}

@media screen and (max-width: 750px) {
    h1{
        font-family: 'HelveticaNeueInterface_thin', 'Courier New';     
        font-size: 100px;
    }
}
@media screen and (max-width: 400px) {
    h1{     
        font-size: 2rem;
    }
}

h2{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New';    
    font-size: 36px;
}

h3{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New';    
    font-size: 1.25rem;
}

h4{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New';    
    font-size: 1.25rem;
}

h5{
    font-family: 'HelveticaNeueInterface', 'Courier New';    
    font-size: 24px;
}

p{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New';    
    font-size: 1.25rem;
}
label{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New'; 
}

a{
    font-family: 'HelveticaNeueInterface_thin', 'Courier New';    
   color: black; 
}

.bold{
    font-family: 'HelveticaNeueInterface' ;
}


</style>