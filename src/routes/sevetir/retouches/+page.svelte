<script>
	import Contenaire from '../../component/Contenaire.svelte';
	import HeroTheme from '../../component/HeroTheme.svelte';
	import ThemeButton from '../../component/ThemeButton.svelte';
	import TitleH2 from '../../component/TitleH2.svelte';
	import RetoucheVetement from '../../component/RetoucheVetement.svelte';
</script>

<HeroTheme
	srcImg="/images/logo/scisor.svg"
	title="Retoucher ses vêtements :
Lieux et Tutos"
></HeroTheme>
<section>
	<Contenaire><h2 class="bold">Réparer ses vêtements, la mode intemporelle !</h2>
		<p>C'est le moment de secouer un peu le game de la mode.</p>
		<p>Plutôt que de balancer tes fringues, pourquoi pas les réparer ?</p>
		<p>
			On sait tous que la mode va plus vite que la lumière, mais au lieu de suivre le rythme,
			pourquoi ne pas ralentir et donner une seconde vie à ton jean préféré? Un coup de couture
			par-ci, un remplacement de bouton par-là, et bam le tour est joué.
		</p>
		<p>Réparer, c'est pas juste économique, c'est un geste rebelle contre la surconsommation.</p>
		<p><span class="bold">Retrouve juste ici quelques retoucheurs sur Bordeaux !</span></p>
	</Contenaire>
	<div class="allContact">
		<RetoucheVetement
			title="Rapid’couture"
			horaire="Mercredi à vendredi 14:00–19:00"
			map="53 Rue du Pas-Saint-Georges, 33000 Bordeaux"
			phone="0984135827"
		></RetoucheVetement>
		<RetoucheVetement
			title="Top Retouches"
			horaire="Mardi à jeudi 11:00–18:30 
        Vendredi et samedi 11:00–18:00"
			map="4 Rue Castillon, 33000 Bordeaux"
			phone="00556449490"
		></RetoucheVetement>
		<RetoucheVetement
			title="Bordeaux Retouches"
			horaire="Mardi à vendredi 14:00–19:00        "
			map="83 Rue Georges Bonnac, 33000 Bordeaux"
			phone="0601028448"
		></RetoucheVetement>
		<RetoucheVetement
			title="Au Premier Fil"
			horaire="Mardi à samedi 10:00–14:000"
			map="42 Rue de Labrede, 33800 Bordeaux"
			phone="0556784063"
		></RetoucheVetement>
	</div>
	<TitleH2>Faire retoucher c’est bien ! Retoucher soi même, c’est mieux !</TitleH2>
	<Contenaire><p>
			L’envie de retoucher te vêtements te prend mais l’idée de laisser faire des retoucheurs te
			gêne ? Pourquoi ne pas apprendre sois même a retoucher tes vêtements dans ce cas ? Grâce a ces
			tutos apprends toi même a réparer tes vêtements ! Et n’oublie pas que rien ne t’empêche d’y
			arriver par toi même !  Alors, la prochaine fois que ton t-shirt préféré décide de te lâcher,
			attrape une aiguille, mets ta playlist préférée en fond, et fais-le revivre.
		</p></Contenaire>
	
	<div class="videos">
		<h3>Les boutons</h3>
		<div class="">
			<iframe
				src="https://www.youtube.com/embed/e-zF07gzJcc"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
			<iframe
				src="https://www.youtube.com/embed/watch?v=EftKvvnUxfQ"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>

		<h3>Les fermetures éclair</h3>
		<div class="">
			<iframe
				src="https://www.youtube.com/embed/6bnQMZ9aYP4"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
			<iframe
				src="https://www.youtube.com/embed/IcmGkrGA3eY"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>
		<h3>Les Trous</h3>
		<div class="">
			<iframe
				src="https://www.youtube.com/embed/gRIyexpw8qQ"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
			<iframe
				src="https://www.youtube.com/embed/KfUvgLW5HbE?si=m8oot3wUMF7Xk0rP"
				title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
				allowfullscreen
			></iframe>
		</div>
	</div>
	<div class="">
		<TitleH2>Un autre article susceptible de vous intéresser</TitleH2>
		<div class="allButton">
			<ThemeButton src="../sevetir/seconde-main" logo="/images/logo/eco.svg"
				>RL’esprit “Seconde main”</ThemeButton
			>
		</div>
	</div>
</section>

<style>
	.videos {
		margin: 0 auto;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
	section {
		width: 100vw;
		padding-left: 5rem;
		padding-right: 5rem;
	}
	@media screen and (max-width: 450px) {
		section {
			padding-left: 1rem;
			padding-right: 1rem;
		}
	}
	p {
		max-width: 900px;
        margin-bottom: 3vh;
	}
	div {
		margin-bottom: 5rem;
	}

	.allContact {
		display: grid;
		grid-template-columns: 1fr 1fr;
		align-items: center;
		justify-items: center;
	}
	@media screen and (max-width: 1300px) {
		.allContact {
			grid-template-columns: 1fr;
		}
	}
	h3 {
		margin-bottom: 3rem;
		margin-top: 1rem;
	}
</style>
