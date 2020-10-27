<script>
  import links from "../../store/links";
  import Header from "../../components/Header.svelte";
  import Main from "../../components/Main.svelte";
  import LeftSide from "../../components/Main/LeftSide.svelte";
  import Definition from "../../components/Main/Definition.svelte";
  import Article from "../../components/Main/Article.svelte";
  export let segment;
  const labels = ["disciplines", "autres"];
</script>
{segment}
<Header title="astronomie" />
<Definition>
  Science des astres, des corps célestes (y compris la Terre) et de la structure
  de l'univers.
</Definition>
<Article>
  <div slot="content">article à venir</div>
</Article>
