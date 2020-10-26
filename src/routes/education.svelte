<script>
  import Header from '../components/Header.svelte';
  import Main from '../components/Main.svelte'
  import LeftSide from '../components/Main/LeftSide.svelte'
  import Definitions from '../components/Main/Definitions.svelte'
  import Article from '../components/Main/Article.svelte'
  // export let segment
  const defs =   [
    "Mise en œuvre des moyens propres à assurer la formation et le développement d'un être humain ; moyens pour y parvenir.",
    "Développement méthodique (d'une faculté, d'un organe).",
  ]
</script>
<!-- <Header {segment} /> -->
<Main>
  <!-- <div slot="side">
    <LeftSide>
      <ul>
        <li>pas encore défini</li>
        <!-- <li>Connaissances</li>
          <li>Phénomènes</li>
          <li>Signes</li>
          <li>Traditions</li>
        </ul>
      </LeftSide>
    </div> -->
    <div  >
      <Header title="éducation" />
    <Definitions {defs}>
      <!-- <ol>
        <li><q>Enrichissement de l'esprit par des exercices intellectuels;</q></li>
        <li><q>Connaissances dans un domaine particulier:</q></li>
        <li><q>Ensemble des phénomènes matériels et idéologiques qui caractérisent un groupe ethnique ou une nation, une civilisation, par opposition à un-e autre;</q></li>
        <li><q>Dans un groupe social, ensemble de signes caractéristiques du comportement de quelqu'un (langage, vêtements, gestes, etc.) qui le différencient de quelqu'un appartenant à une autre couche sociale que lui;</q></li>
        <li><q>Ensemble de traditions technologiques et artistiques caractérisant tel ou tel stade de la préhistoire.</q></li>
      </ol>
        <p>Le sujet étant vaste, il sera exploré respectivement aux définitions.</p> -->
      <!-- Science des astres, des corps célestes (y compris la Terre) et de la structure de l'univers. -->
      
    </Definitions>
    <Article>
      <div slot="content">

        article à venir
      </div>

    </Article>
  </div>
</Main>
