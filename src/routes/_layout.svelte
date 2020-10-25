<script>

	import Nav from '../components/Nav.svelte';
	import Header from '../components/Header.svelte';
	import Main from '../components/Main.svelte';
	import LeftSide from '../components/Main/LeftSide.svelte';
	import Definition from '../components/Main/Definition.svelte';
	import Article from '../components/Main/Article.svelte';
	import Footer from '../components/Footer.svelte';
	export let segment;
	const segArr = []
	segArr[0] = segment
	const pageTitle = segArr[0] || "Bienvenue!"
	// $: if (segment == undefined) pageTitle = "Bienvenue!"
	// $: console.log(pageTitle)

</script>
<!-- 
<style>
	main {
		position: relative;
		max-width: 56em;
		background-color: white;
		padding: 2em;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style> -->

<Nav {segment}/>
<!-- <Header {pageTitle } /> -->
<!-- <Main >
</Main> -->
<div class="mt-5">
	<slot />

</div>


<Footer />