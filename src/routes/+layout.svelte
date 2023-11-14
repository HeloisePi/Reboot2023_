<script>
	import Footer from "./component/Footer.svelte";
import Header from "./component/Header.svelte";

</script>
<Header />
<div class="app">
	<main>
		<slot />
	</main>

	<Footer />
</div>

<style>
	</style>