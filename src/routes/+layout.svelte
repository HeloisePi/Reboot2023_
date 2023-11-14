<script>
	import Header from "./component/Header.svelte";

</script>
<Header />
<div class="app">
	<main>
		<slot />
	</main>

	<footer>
		<p>
			© 2023 - Tous droits réservés à nous  - Mentions légales
		</p>
	</footer>
</div>

<style>
	</style>