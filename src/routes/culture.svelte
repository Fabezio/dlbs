<script>
	import Header from '../components/Header.svelte';
  // import LeftSide from '../components/Main/LeftSide.svelte';
  import Main from '../components/Main.svelte'
  import LeftSide from '../components/Main/LeftSide.svelte'
  import Definition from '../components/Main/Definition.svelte'
  import Article from '../components/Main/Article.svelte'
  
  const labels = [
    'enrichissement',
    'connaissances',
    'phénomènes', 
    'signes',
    'traditions'
  ]
	// import LeftSide from '../components/LeftSide.svelte';
</script>
<!-- <Header pageTitle="culture" /> -->


<Main>
	<div slot="side">
		<LeftSide >
      <ul>
          <li>Enrichissement</li>
          <li>Connaissances</li>
          <li>Phénomènes</li>
          <li>Signes</li>
          <li>Traditions</li>
        </ul>
                <!-- <LeftSide {labels}> -->
		</LeftSide>
	</div>
	<div slot="global" >
    <Definition title="Définitions">
      <ul>
        <li><q>Enrichissement de l'esprit par des exercices intellectuels;</q></li>
        <li><q>Connaissances dans un domaine particulier:</q></li>
        <li><q>Ensemble des phénomènes matériels et idéologiques qui caractérisent un groupe ethnique ou une nation, une civilisation, par opposition à un-e autre;</q></li>
        <li><q>Dans un groupe social, ensemble de signes caractéristiques du comportement de quelqu'un (langage, vêtements, gestes, etc.) qui le différencient de quelqu'un appartenant à une autre couche sociale que lui;</q></li>
        <li><q>Ensemble de traditions technologiques et artistiques caractérisant tel ou tel stade de la préhistoire.</q></li>
      </ul>
      <p>Le sujet étant vaste, il sera exploré respectivement aux définitions.</p>
      <!-- Science des astres, des corps célestes (y compris la Terre) et de la structure de l'univers. -->
    
    </Definition>
    <Article>
      <div slot="content">

        article à venir
      </div>

    </Article>
  </div>
</Main>
