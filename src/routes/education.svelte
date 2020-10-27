<script>
  import Header from "../components/Header.svelte";
  import Main from "../components/Main.svelte";
  import LeftSide from "../components/Main/LeftSide.svelte";
  import Definitions from "../components/Main/Definitions.svelte";
  import Article from "../components/Main/Article.svelte";
  // export let segment
  const defs = [
    "Mise en œuvre des moyens propres à assurer la formation et le développement d'un être humain ; moyens pour y parvenir.",
    "Développement méthodique (d'une faculté, d'un organe).",
  ];
</script>

<Header title="éducation" />
<Definitions {defs} />

<Article>
  <div slot="content">article à venir</div>
</Article>
