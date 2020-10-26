<script>
	
	import Header from '../components/Header.svelte';
	import Main from '../components/Main.svelte';
	import LeftSide from '../components/Main/LeftSide.svelte';
	// import Definition from '../components/Main/Definition.svelte';
	import Article from '../components/Main/Article.svelte';
	import links from "../store/links"
	export let segment
	// export let segArr
	// export const pageTitle = "Accueil"
</script>

<!-- <Header {segment} /> -->
<Main>
	<!-- <div slot="side">
		<LeftSide labels={links} {segment}>

			
			<!-- <span>y'a rien là</span> 
		</LeftSide>
	</div> -->
	<div >

		<div class="bg-light py-3 px-auto">
			<figure  class="text-center">
				<img src="img/fleche verte.png" height="100" alt="fleche" >

			</figure>

		</div>
		<!-- <div class="row">
			<div class="col-offset-1 col-md-8">

			</div>
		</div>
		.col-md-8 -->
		<Header title="accueil" header="Bienvenue!" />
		<Article>
			<div slot="content">

			
			<!-- <h2>Bienvenue</h2> -->
			<p>Ce site a pour vocation de guider les visiteurs dans leur quête visant à:</p>
			<ul>
			  <li>approfondir des connaissances,</li>
			  <li>satisfaire leur curiosité,</li>
			  <li>rechercher des liens,</li>
			  <li>etc.</li>
			</ul>
			<p>Plusieurs rubriques éducatives sont disponibles et contiennent textes, médias et liens.<br />Vous y trouverez:</p>
			<ul>
			  <li>les principes relatifs aux civilités avec les conduites à tenir (transports, secours, savoir vivre),</li>
			  <li>l’éducation (scolaire, parentale, professionnelle),</li>
			  <li>l’informatique,</li>
			  <li>les sciences,</li>
			  <li>les orientations professionnelles.</li>
			</ul>
			<p>En clair il s’agit d’un supermarché de l’information. Des liens sont disponibles ci-dessous pour vous permettre de me faire part de vos remarques et suggestions, lesquelles sont vivement encouragées! En effet l’enrichissement d’un site provient toujours d’un travail en communauté.</p>
			<p>Sur ce assez de blabla, place à l’info. Car le savoir est aussi un devoir</p>
</div>
		</Article>

	</div>

</Main>
<!-- <section>
	
	<article>
	</article>
	<aside></aside>
  </section> -->

<!-- 
<style>
	h1, figure, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>
 -->

