<script>
	import Header from '../components/Header.svelte';
  import LeftSide from '../components/Main/LeftSide.svelte';
  
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

<div class="w-75 mx-auto">
  <!-- <h3>Définitions</h3> -->
  <ul>
    <li><q>Enrichissement de l'esprit par des exercices intellectuels;</q></li>
    <li><q>Connaissances dans un domaine particulier:</q></li>
    <li><q>Ensemble des phénomènes matériels et idéologiques qui caractérisent un groupe ethnique ou une nation, une civilisation, par opposition à un-e autre;</q></li>
    <li><q>Dans un groupe social, ensemble de signes caractéristiques du comportement de quelqu'un (langage, vêtements, gestes, etc.) qui le différencient de quelqu'un appartenant à une autre couche sociale que lui;</q></li>
    <li><q>Ensemble de traditions technologiques et artistiques caractérisant tel ou tel stade de la préhistoire.</q></li>
  </ul>
  <p>Le sujet étant vaste, il sera exploré respectivement aux définitions.</p>

</div>


<div class="row">
  <div class="col-md-3 col-sm-12">
    <LeftSide {labels}>
      <!-- <ul>
        <li>Enrichissement</li>
        <li>Connaissances</li>
        <li>Phénomènes</li>
        <li>Signes</li>
        <li>Traditions</li>
      </ul> -->
      
    </LeftSide>
    
  </div>
  <div class="col-md-9 col-sm-12">
    
    <article>
    <section>
      <p><em></em></p>
    </section>
    
    <h3></h3>
    <p></p>
  </article>
  </div>
</div>
