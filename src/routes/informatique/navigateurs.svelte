<script>
  import Header from "../../components/Header.svelte";
  import Definition from "../../components/Main/Definition.svelte";
  import Article from "../../components/Main/Article.svelte";
  // import Main from "../../components/Main.svelte";
  // import LeftSide from "../../components/Main/LeftSide.svelte";
  // export let segment
  // const labels = ["Windows", "Mac", "BSD", "GNU / Linux"];
</script>

<Header title="Navigateurs internet" />
<Definition>
  <!-- Science des astres, des corps célestes (y compris la Terre) et de la structure de l'univers. -->
  <q>Un navigateur web correspond à un logiciel évolutif et complexe qui permet
    de naviguer sur Internet à partir d'un ordinateur, d'un téléphone ou d'une
    tablette. Le premier a été créé en 1990. Exemple : Mozilla Firefox est un
    navigateur web.</q>
</Definition>
<Article>
  <div slot="content">
    <h3>Les navigateurs</h3>
    <p>
      Chaque OS a développé son propre navigateur web, tous sont accessibles
      depuis n’importe quelle plateforme. Chacun a évolué en fontion des besoins
      et spécificités des utilisateurs et en entreprises.
    </p>
    <p>Il y a à ce jour cinq grandes plateformes de navigation:</p>
    <ol>
      <li>Firefox, développée par Mozilla (Linux)</li>
      <li>Safari (Apple)</li>
      <li>Internet Explorer et Edge (Windows)</li>
      <li>Chrome (Google)</li>
      <li>Opera</li>
      <li>Vivaldi</li>
      <li>Brave</li>
    </ol>
    <p>
      Il en existe bien d'autres, je n'ai cité ici que les plus connus. Pour de
      plus amples détails, veuillez consulter les liens connexes ci-contre.<br />
    </p>
  </div>
</Article>
