<script>

	import Nav from '../components/Nav.svelte';
	import Header from '../components/Header.svelte';
	import Main from '../components/Main.svelte';
	import LeftSide from '../components/Main/LeftSide.svelte';
	import Definition from '../components/Main/Definition.svelte';
	import Article from '../components/Main/Article.svelte';
	import Footer from '../components/Footer.svelte';
	export let segment;
	$: if (segment == undefined) segment = "accueil"
	$: console.log(segment)

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
<Header {segment} />
<Main >
</Main>
	<slot />

<Footer />