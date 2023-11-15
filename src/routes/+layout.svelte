<script>
	import Footer from "./component/Footer.svelte";
	import Header from "./component/Header.svelte";
	import HeaderMobile from "./component/HeaderMobile.svelte";

</script>

<div class="headerdesktop">
	<Header />
</div>
<div class="headerMobile">
	<HeaderMobile />
</div>

<div class="app">
	<main>
		<slot />
	</main>

	<Footer />
</div>

<style>
	.headerMobile{
			display: none;
		}

  @media screen and (max-width: 500px) {
        footer p {
            font-size: 14px;
        }
    }
	@media screen and (max-width: 870px) {
		.headerMobile{
			display: block;
		}
		.headerdesktop{
			display: none;
		}
        
    }

	</style>