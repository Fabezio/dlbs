<script>
  import Header from "../components/Header.svelte";
  import Article from "../components/Main/Article.svelte";
  // import Main from "../components/Main.svelte";
  // import LeftSide from "../components/Main/LeftSide.svelte";
  // import Definition from '../components/Main/Definition.svelte';
  // import links from "../store/links";
  // export let segment;
  // export let segArr
  // export const pageTitle = "Accueil"
</script>

<div class="">
  <figure class="text-center ">
    <img src="img/fleche verte.png" class="w-75" alt="fleche" />
  </figure>
  <Header title="accueil" header="Bienvenue!" />
  <Article>
    <div slot="content">
      <!-- <h2>Bienvenue</h2> -->
      <p>
        Ce site a pour vocation de guider les visiteurs dans leur quête visant à:
      </p>
      <ul>
        <li>approfondir des connaissances,</li>
        <li>satisfaire leur curiosité,</li>
        <li>rechercher des liens,</li>
        <li>etc.</li>
      </ul>
      <p>
        Plusieurs rubriques éducatives sont disponibles et contiennent textes,
        médias et liens.<br />Vous y trouverez:
      </p>
      <ul>
        <li>
          les principes relatifs aux civilités avec les conduites à tenir
          (transports, secours, savoir vivre),
        </li>
        <li>l’éducation (scolaire, parentale, professionnelle),</li>
        <li>l’informatique,</li>
        <li>les sciences,</li>
        <li>les orientations professionnelles.</li>
      </ul>
      <p>
        En clair il s’agit d’un supermarché de l’information. Des liens sont
        disponibles ci-dessous pour vous permettre de me faire part de vos
        remarques et suggestions, lesquelles sont vivement encouragées! En effet
        l’enrichissement d’un site provient toujours d’un travail en communauté.
      </p>
      <p>
        Sur ce assez de blabla, place à l’info. Car le savoir est aussi un devoir
      </p>
    </div>
  </Article>
</div>

