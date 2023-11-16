<script>
	import Hero from '../component/Hero.svelte';
	import TitleH2 from '../component/TitleH2.svelte';
	import Name from '../component/Name.svelte';
</script>

<Hero title="Qui sommes-nous ?" />
<section>
	<TitleH2>Frynge</TitleH2>
	<p>
		Frynge, c’est une équipe d’étudiants dans les métiers du web. Sensibilisés à la cause
		environnementale, on a eu à cœur de partager des tips du quotidien pour entrer dans une démarche
		de décroissance. Parce que <span class="bold">oui</span>, tout le monde peut participer à cette
		décroissance.
	</p>

	<p>
		Notre but ? <span class="green">Viser un public étudiant local et proposer des solutions et des bons plans
		accessibles, même pour les petits budgets.</span>
	</p>

	<TitleH2>La Décroissance, C’EST QUOI ?</TitleH2>

	<p>
		La décroissance, c’est l’idée que l’augmentation des richesses ne conduit pas au bien-être
		social.
	</p>

	<p>
		Dès 1970, des économistes étudient le modèle capitaliste et ses aboutissants. Ils arrivent à la
		conclusion que ce modèle n’a pas réellement tenu ses promesses :
		<li>
			Même si on produit à longueur de journée, on fait jamais partie de ceux qui en profitent (ex:
			chômage en masse, précarité…)
		</li>
		<li>
			Le métro-boulot-dodo ne rend pas heureux (ex: aliénation au travail, accidents, stress…)
		</li>
		<li>
			On sacrifie la planète pour un Iphone qui dure trois ans (ex: pollution, disparition d’espèces
			animales…)
		</li>
	</p>

	<p>
		La décroissance, c’est avant tout un modèle sociétal, ce qui veut dire que t’as peu de chances
		d’y arriver si t’es tout seul.
	</p>

	<p>
		Cependant, il n’est pas impossible pour l’individu de se pencher sur la question et de s’en
		servir pour vivre de façon plus responsable : c’est <span class="bold">notre objectif.</span>
	</p>

	<p>
		On sait que les jeunes ont souvent plus de considération pour les questions écologiques et
		sociales que leurs aînés, mais les moyens manquent. C’est là qu’on intervient : <span class="green">notre but, c’est
		de te montrer comment implémenter la décroissance au quotidien, sans pour autant que tu aies à
		te priver.</span> C’est d’ailleurs un élément qui est au centre du concept de décroissance : viser la
		décroissance, c’est aller vers une simplicité volontaire qui ne nuit pas à ton bonheur.
	</p>
	<p>
		Concrètement, la décroissance, on te propose de t’y essayer sous trois axes de réflexion (et de
		bons plans) différents :
	</p>

	<p><li class=" bold">Comment consommer moins? → En consommant mieux !</li></p>
	<p>
		Par exemple : acheter à petit prix ce qui est déjà produit, l’’éco-conception, trouver des
		alternatives (ex: transports en commun)
	</p>

	<p>
		La décroissance n’est pas similaire au développement durable au sens où le développement durable
		propose la possibilité de produire de façon responsable tandis que la décroissance considère
		qu’il faut absolument remettre en question le modèle de production dans son entièreté.
	</p>

	<p>
		Cependant, à l’échelle individuelle, le développement durable reste une idée que l’on peut assez
		facilement mettre en place, et c’est elle qui se rapproche le plus d’un premier pas vers la
		décroissance.
	</p>
	<p><li class="bold">Comment rallonger la vie de ce qu’on a déjà? → En y prenant soin !</li></p>
	<p>
		Comment réparer nos vêtements issus de la fast-fashion? Comment conserver notre nourriture pour
		ne pas jeter? On a des réponses à toutes tes questions.
	</p>

	<p>
		Le second pas vers la décroissance, <span class="green">c’est de refuser de consommer.</span> Mais le but n’est pas de
		tirer une croix sur notre confort quotidien. Il faut donc trouver de nouvelles façons
		d’entretenir, protéger et réparer ce qu’on possède déjà. Une autre solution serait le troc.
	</p>
	<p>
		<li class="bold">
			Comment consommer moins sans ressentir un manque ? → Une sobriété réussie, c’est une sobriété
			conviviale !
		</li>
	</p>
	<p>
		C’est à dire sortir à petits prix, faire vivre la scène artistique locale, remplacer son temps à
		produire ou consommer par du bénévolat.
	</p>

	<p>
		La décroissance prône l’épanouissement des individus et la convivialité. Le refus de consommer
		s’ajoute à <span class="green">un désir de faire communauté, et de profiter d’expériences</span> au lieu de produits.
	</p>

	<p>
		Si tu veux en lire plus au sujet de la décroissance, on t’invite à regarder <a
			href="https://www.francetvinfo.fr/monde/environnement/l-article-a-lire-pour-tout-comprendre-a-la-decroissance-pronee-par-certains-candidats-a-la-primaire-ecologiste_4747435.html"
			>cet article</a
		>.
	</p>
</section>

<style>
	section {
		width: 100vw;
		padding-left: 5rem;
		padding-right: 5rem;
		margin-bottom: 5rem;
	}
	@media screen and (max-width: 450px) {
		section {
			padding-left: 1rem;
			padding-right: 1rem;
		}
	}
	p {
		margin-bottom: 2rem;
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
