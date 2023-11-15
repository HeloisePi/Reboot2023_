<script>
	import Hero from "./component/Hero.svelte";
    import TitleH2 from "./component/TitleH2.svelte";
    import Theme from "./component/Theme.svelte";
</script>
<Hero title="Frynge"/>
<section>
    <TitleH2>Description</TitleH2>
    <p class="textDescription">Bienvenue sur Frynge, la plateforme bons plans qui t’aide à entrer dans une démarche de décroissance. Tutos, activités, astuces, bons plans… fais le plein d’idées à petit budget.</p>
    <TitleH2>Bons plans</TitleH2>
    <div class="BoutonsTheme">
        <Theme logo="/images/logo/hobbies.svg" > Se<br> Divertir</Theme>
        <Theme logo="/images/logo/clothes.svg" >Se<br> vêtir</Theme>
        <Theme logo="/images/logo/food.svg" >Se<br> nourrir</Theme>
    </div>
    <TitleH2>Nos vidéos</TitleH2>
    <div class="videos">
        <iframe src="https://www.youtube.com/embed/cekwQzDzkVs?si=3FvNZ6eU2yeZE9Ez" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        <iframe src="https://www.youtube.com/embed/cekwQzDzkVs?si=3FvNZ6eU2yeZE9Ez" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        <iframe src="https://www.youtube.com/embed/cekwQzDzkVs?si=3FvNZ6eU2yeZE9Ez" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>

</section>

<style>
    .textDescription{
        margin-bottom: 5rem;
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
    }
    @media screen and (max-width: 520px) {
        .videos iframe{
            width: 200px;
            height: 150px;
        }
    }

    iframe{
        border-radius: 10px;
        width: 350px;
        height: 200px;
    }
    section{
        width: 100vw;
        padding-left: 5rem;
        padding-right: 5rem;
    }
    .BoutonsTheme{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        justify-items: center;

        padding-bottom: 5rem;
        margin-left: 50%;
        transform: translateX(-50%);
        width: 100vw;
    }
    
</style>