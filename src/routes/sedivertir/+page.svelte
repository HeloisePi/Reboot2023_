<script>
	import Contenaire from '../component/Contenaire.svelte';
	import HeroTheme from '../component/HeroTheme.svelte';
	import Suggestion from '../component/Suggestion.svelte';
	import ThemeButton from '../component/ThemeButton.svelte';
	import TitleH2 from '../component/TitleH2.svelte';
</script>

<HeroTheme srcImg="/images/logo/hobbies.svg" title="Se divertir"></HeroTheme>
<section>
	<Contenaire>
		<h2 class="bold">Le bien-être, on en fait quoi ?</h2>
		<p>Timothée Parrique (docteur en sciences économiques) explique que : <span class="green">“La décroissance repose sur
			une réduction planifiée et démocratique de la production et de la consommation dans les pays
			riches pour réduire les pressions environnementales et les inégalités, tout en améliorant le
			bien-être.”</span></p>
            <p>Je sais, la définition peut paraître un peu technique ! Je te propose qu’on
			s’arrête sur un point : <span class="bold">le bien-être</span>. Tu t’es déjà senti isolé ? Trop souvent, tu passes tes
			week-ends chez toi à tourner en rond ? </p>
            <p>J’en suis convaincue, l’épanouissement social et
			culturel peut être une source de bien-être. Voilà pourquoi je te propose ici plein de bons
			plans pour sortir à petits prix !
		</p>
	</Contenaire>

	<div class="">
		<TitleH2>Nos Articles</TitleH2>
		<div class="allButton">
			<ThemeButton src="../sedivertir/boireunverre" logo="/images/logo/cocktail.svg"
				>Schlouk map, pour boire des verres sans se ruiner !</ThemeButton
			>
			<ThemeButton src="../sedivertir/eturecup" logo="/images/logo/light.svg"
				>Étu’Ré quoi ?</ThemeButton
			>
		</div>
	</div>
	<Suggestion src="https://openagenda.com/carte-jeune-bordeaux-metropole/events/cine-petitdej-mon-voisin-totoro" srcImg="/images/suggestions/1.png" title="Ciné Petit’Déj – Mon Voisin Totoro">Séance précédée d’un petit déjeuner offert, en partenariat avec la boulangerie Maison Valé. Replongez dans le classique de Miyazaki avant de découvrir à La Lanterne son nouveau film.</Suggestion>
	<Suggestion src="https://openagenda.com/relache-13/events/les-veilleurs-de-nuit?sharemodal=1" srcImg="/images/suggestions/2.png" title="Les Veilleurs de Nuit">Un court-métrage de Christophe Brachet et des oeuvres de Richard Giacobetti seront le point de départ d'un échange poétique entre les deux artistes et la journaliste et animatrice Sabine Quindou.</Suggestion>
</section>

<style>
	section {
		width: 100vw;
		padding-left: 5rem;
		padding-right: 5rem;
		display: flex;
		flex-direction: column;
		gap: 5rem;
		padding-bottom: 5rem;
	}
	@media screen and (max-width: 450px) {
        section{
        padding-left: 1rem;
        padding-right: 1rem;
    }
    }

    p {
        margin-bottom: 3vh;
    }

	h2 {
		margin-bottom: 2rem;
	}
	.allButton {
		display: flex;
		gap: 2rem;
	}
	@media screen and (max-width: 880px) {
        section .allButton{
            flex-direction: column;
            justify-content: center;
            align-items: center;
    }
    }
</style>
