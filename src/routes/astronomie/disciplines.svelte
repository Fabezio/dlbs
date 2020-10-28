<script>
  import Header from "../../components/Header.svelte";
  import Definition from "../../components/Main/Definition.svelte";
  import Article from "../../components/Main/Article.svelte";
  export let segment;
  // import links from "../../store/links";
  // import Main from "../../components/Main.svelte";
  // import LeftSide from "../../components/Main/LeftSide.svelte";
  // const labels = ["disciplines", "autres"];
</script>

{segment}
<Header title="disciplines" />
<Definition>
  Branche de la connaissance, des études (dans ce contexte)
</Definition>
<Article>
  <div slot="content">
    <h3>Astrophysique</h3>
    <h3>Astrométrie</h3>
    <h3>Astronautique</h3>
    article à venir</div>
</Article>
