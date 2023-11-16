<script>
	import Contenaire from '../../component/Contenaire.svelte';
	import HeroTheme from '../../component/HeroTheme.svelte';
</script>

<HeroTheme srcImg="/images/logo/food.svg" title="Se nourrir à faible impact et moindre frais"
></HeroTheme>

<section>
	<Contenaire
		><p>
			S’alimenter de manière responsable et faire des économies ne semblent pas toujours être
			compatibles. Acheter local ou acheter bio paraît être un luxe, toutefois, <span class="green"
				>il existe des initiatives locales ou nationales pour t’aider à franchir le cap</span
			> :
		</p>
		<p>
			<li>
				Paniers anti-gaspi : grâce à ces sites, tu peux récupérer les invendus
				de commerçants près de chez toi à moindre prix, il en existe plusieurs à toi de choisir : Too
				Good to Go, Phenix, etc.
			</li>
			<li>
				L’épicerie “Nous Anti Gaspi” est une épicerie propose des produits à prix cassé pour les
				sauver de la poubelle, tu as aussi le droit à une remise étudiante en début de mois ; pour
				en savoir plus <a href="https://antigaspi.com/actualites-antigaspi/10-pour-les-etudiants/"
					>rendez-vous ici</a
				>.
			</li>
			<li>
				<span class="bold">Les marchés</span> : des produits locaux, souvent moins cher en magasins et l’astuce est d’y passer
				juste avant la fermeture pour des prix encore plus bas. 
                Retrouve la carte des marchés <a href="https://plan.bordeaux.fr/bordeaux/?context=NSrC">ici</a>.
	
			</li>
			<li>
				Aller directement auprès du producteur pour acheter ses produits peut permettre de faire de
				belles économies puisque vos produits n’ont pas à parcourir la France entière pour vous
				atteindre, si tu veux approfondir, tu peux en lire plus <a href="https://www.sudouest.fr/environnement/ou-acheter-ses-fruits-et-legumes-directement-a-la-ferme-dans-la-metropole-bordelaise-4693642.php">par ici.</a>
				
			</li>
			<li>
				La gemme est une monnaie locale de Gironde qui permet de s’acheter des produits aux
				producteurs locaux, pour en profiter il suffit de <a href="https://lagemme.org/">cliquer ici</a> 
			</li>
		</p>
	</Contenaire>
</section>

<style>
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
		margin-bottom: 2vh;
	}

	a {
		color: #21864f;
		font-weight: bold;
	}

	a:hover {
		text-decoration: underline;
		text-underline-offset: 0.4vh;
	}

    li {
        margin-bottom: 1rem;
    }
</style>
