<script>
  import Header from "../../components/Header.svelte";
  import Main from "../../components/Main.svelte";
  import LeftSide from "../../components/Main/LeftSide.svelte";
  import Definitions from "../../components/Main/Definitions.svelte";
  import Article from "../../components/Main/Article.svelte";
  // import LeftSide from '../components/Main/LeftSide.svelte';
  // export let segment
  const labels = [
    "enrichissement",
    "connaissances",
    "phénomènes",
    "signes",
    "traditions",
  ];
  const defs = [
    "Enrichissement de l'esprit par des exercices intellectuels",
    "Connaissances dans un domaine particulier",
    "Ensemble des phénomènes matériels et idéologiques qui caractérisent un groupe ethnique ou une nation, une civilisation, par opposition à un.e autre",
    "Dans un groupe social, ensemble de signes caractéristiques du comportement de quelqu'un (langage, vêtements, gestes, etc.) qui le différencient de quelqu'un appartenant à une autre couche sociale que lui",
    "Ensemble de traditions technologiques et artistiques caractérisant tel ou tel stade de la préhistoire.",
  ];
  // import LeftSide from '../components/LeftSide.svelte';
</script>

<Header title="culture" />
<Definitions {defs} />

<!-- </Definition> -->
<Article>
  <div slot="content">article à venir</div>
</Article>
