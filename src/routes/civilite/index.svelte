<script>
  import Header from '../../components/Header.svelte';
  import Main from '../../components/Main.svelte'
  import LeftSide from '../../components/Main/LeftSide.svelte'
  import Definition from '../../components/Main/Definition.svelte'
  import Article from '../../components/Main/Article.svelte'
  // export let segment
</script>
<!-- <Header pageTitle="civilité" /> -->


<Main>
  <div slot="side">
    <!-- <LeftSide>
      Transports
		</LeftSide> -->
	</div>
	<div  >
    <Header title="civilité" />
    <Definition>
      Observation des convenances en usage chez les gens qui vivent en société; politesse, courtoisie
      
    </Definition>
    <Article>
      <div slot="content">
        <h3>Transports</h3>
      <p>
        S'il y a une chose qui énerve tout un chacun, c'est bien le manque de réactivité des usagers dans les transports en commun; par exemple les réseaux ferrés franciliens: aux heures de pointe les trams et métros sont bondés.
        Lors d'une desserte, il est rare de voir les usagers s'effacer de leur propre initiative pour laisser passer un co-usager, beaucoup sont en mode<em>poteau</em>, il faut souvent jouer des coudes pour se faufiler jusqu’au seuil ou donner de la voix.
        Ses comparses vont avoir à cheminer de la même façon plus.
        Or le bon sens voudrait que tout le monde descende en même temps afin de faciliter le passage, réorganiser la foule en fonction des futurs sortants, désankyloser ses membres.
        De plus il y a toujours quelqu'un pour vous bousculer sans ménagement, manifester sa mauvaise humeur, s'en prendre à son voisin pour un fait parfaitement trivial, ledit voisin faisant monter la mayonnaise de son côté car chacun veut avoir le dernier mot, et ce au dépens des autres usagers dont le souci le plus urgent est un peu de calme après une journée éprouvante.
      </p>
      <p>
        De leur côté les usagers montants ne sont pas en reste de mauvaise grâce, car ils s'agglutinent impatiemment devant les portes, témoignant d'un manque de bon sens égal à celui des précédemment cités puisqu'ils empêchent la descente de ces derniers.
        Et tout cela malgré les mises en garde et messages répétés oralement ou par l'intermédiaire d'affiches que l'on ne peut manquer.
      </p>
      <p>
        Pourquoi un tel manquement aux règles les plus élémentaires de bonne conduite lors d'un voyage partagé?
        Pour commencer une grosse lacune dans l'éducation.
        Ensuite une indifférence généralisée doublée d'un instinct de conservation futile dans ce cas: le fait d'être massés comme des sardines en boîte est complètement contre nature.
      </p>
      <h4>Solutions envisageables:</h4>
      <ul>
        <li>sensibiliser les usagers pour un meilleur emprunt des transports en commun ;</li>
        <li>diffuser lesdites méthodes sur une bande de communication plus large que de simples messages ponctuels ou affiches.</li>
      </ul>

        <!-- article à venir -->
      </div>

    </Article>
  </div>
</Main>
