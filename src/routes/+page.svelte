<script>
	import Buttons from "./component/Buttons.svelte";
	import Carousel from "./component/Carousel.svelte";

    import Theme from "./component/Theme.svelte";
	
	
	let colors = ['red', 'orange', 'yellow', 'green', 'blue', 'purple']
</script>

<h1>Welcome to SvelteKit</h1>
<p>hello</p>

<Theme title="Nourir" description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi adipisci eius voluptatibus minus, aspernatur at fugiat. Perspiciatis, alias? Hic, quae esse assumenda magnam deserunt quos voluptate iusto! Debitis, quo optio?" />
<Theme title="Manger" description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi adipisci eius voluptatibus minus, aspernatur at fugiat. Perspiciatis, alias? Hic, quae esse assumenda magnam deserunt quos voluptate iusto! Debitis, quo optio?" />

<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<p> bonjour lol </p>
<Buttons description="merofjiemrofijmefroi"></Buttons>
<Carousel autoplay="2000">
	{#each colors as color, index (index)}
	  <div style="background-color: {color}" />
	{/each}
	<span slot="left-control">Left</span>
	<span slot="right-control">Right</span>
<style>
	div {
		height: 8rem;
		width: 8rem;
	}
	
	span {
		display: inline-block;
		margin-top: 6rem;
	}
</style>