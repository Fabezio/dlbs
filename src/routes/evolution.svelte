<script>
  import Header from "../components/Header.svelte";
  import Definitions from "../components/Main/Definitions.svelte";
  import Article from "../components/Main/Article.svelte";
  const defs = [
    "Mouvement réglé de troupes",
    "(Au pluriel: ) Suite de mouvements variés",
  ];
  // import Main from "../components/Main.svelte";
  // import LeftSide from "../components/Main/LeftSide.svelte";
  // export let segment
</script>

<Header title="évolution" />
<Definitions {defs} />

<Article>
  <div slot="content">article à venir</div>
</Article>
