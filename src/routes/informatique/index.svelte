<script>
	import Header from '../../components/Header.svelte';
  import Main from '../../components/Main.svelte'
  import LeftSide from '../../components/Main/LeftSide.svelte'
  import Definition from '../../components/Main/Definition.svelte'
  import Article from '../../components/Main/Article.svelte'
  // export let segment
  const labels = [
    "Windows",
    "Mac",
    "BSD",
    "GNU / Linux",
    
      ]
</script>
<!-- <Header pageTitle="informatique" /> -->

<Main>
  <!-- <div slot="side">
    <LeftSide {labels} />
      
	</div> -->
	<div >
    <Header title="informatique" />
    <Definition>
      <!-- Science des astres, des corps célestes (y compris la Terre) et de la structure de l'univers. -->
      <q>Science du traitement rationnel, notamment par machines automatiques, de l'information considérée comme le support des connaissances humaines et des communications dans les domaines technique, économique et social (définition académique)</q>
    
    </Definition>
    <Article>
      <div slot="content">
        <h3>De quelles machines parle-t-on?</h3>
        <p>
          Toute machine capable de traiter automatiquement une série d’informations appelées instructions, contenue dans un logiciel.
          Ces logiciels comprennent aujourd’hui un nombre conséquent de lignes de code (appelé ainsi car il est incompréhensible pour un non-initié).
          Appelé aussi programme ou application, il permet de rendre accessible à l’utilisateur des fichiers de toutes sortes (écrits, audio, vidéo), interagir avec un périphérique (imprimante, manette, souris…), guider son héros préféré dans de palpitantes aventures, voire de créer d’autres logiciels.
          Il est également possible de piloter d’autres machines.
          Lesdites machines sont nos ordinateurs, nos smartphones et nos tablettes.
          Quel que soit le constructeur, elles ont toutes en commun qu’elles utilisent un logiciel centralisateur appelé système d’exploitation, lequel permet de faire correspondre l’homme et la machine.
          Seuls diffèrent le matériel et les logiciels, chacun ayant ses spécificités.<br />
        </p>
        <h3>Les systèmes d'exploitation ou OS</h3>Les grandes familles informatiques sont au nombre de trois, quatre avec Android, sans compter les développements parallèles :
        <p></p>
        <ol>
          <li>MacOs (noyau Unix)</li>
          <li>Windows (noyau Microsoft)</li>
          <li>Linux (noyau Kernel)</li>
          <li>Android (noyau Kernel)</li>
        </ol>
        <p>
          Un noyau est une des parties fondamentales d’un système d'exploitation.
          Il gère les ressources de l'ordinateur et permet aux différents composants — matériels et logiciels — de communiquer entre eux.<br />
        </p>
        <h3>Quel système d’exploitation choisir</h3>
        <p>Chaque OS a ses avantages et inconvénients.</p>
        <ul>
          <li><strong>Apple</strong> est extrêmement (voire exagérément) onéreux mais a le mérite d’être<strong>stable et entièrement sécurisé</strong>.
            En outre, c’est le pionnier de l’informatique. Si vous n'avez pas peur de débourser et qu'il vous faut impérativement un systeme fiable, c'est vers Apple qu'il faut vous tourner.
          </li>
          <li><strong>Windows</strong>, bien que plus accessible, a des défauts de stabilité et il faut fréquemment le mettre à jour pour pallier aux ‘failles de sécurité’.
            D’aucuns vous diront que ces failles ont été glissées intentionnellement pour perpétuer le commerce du logiciel.
            En réalité, les produits Microsoft fonctionnent comme un puzzle numérique.
          </li>
          <li><strong>Linux</strong> est entièrement gratuit et stable.<br />Pour ses nombreuses qualités, il est le fournisseur de bon nombre d’utilisateurs particuliers ou professionnels dont le principal souci est la stabilité à long terme.
            En raison de sa gratuité et de sa fiabilité, il est diabolisé par ses deux concurrents qui le font passer pour un système pas très catholique, usité en grande majorité par des hackers de tous poils.
            La vérité est que ce système a été conçu par des milliers de développeurs et que son code source est disponible sur la toile et peut être utilisé, modifié, modulé pour convenir à l’utilisateur.<br />Dur à maitriser pour qui n’est pas habitué, il se décline en d’innombrables versions, dont Debian, CentOS, Mandrive, Fedora, et le fameux Ubuntu.
            En plus d’être gratuit et stable, il n’a pas besoin d’antivirus, de défragmentation, car le système est tellement bien pensé qu’il se gère tout seul comme un grand.<br />De plus tous les outils bureautiques sont fournis.
            Seul inconvénient : étant tout un utilitaire son répertoire de gaming n’est pas aussi étendu que ses concurrents.
            En outre la compatibilité peut être un problème si vous avez des pièces rares.
            Sans oublier quelques difficultés d’installation si vous souhaitez la réaliser par vous-même.
          </li>
          <li><strong>Android</strong> quant à lui a le même noyau que Linux mais propose beaucoup de logiciels entravés par des montagnes de pubs dans leurs versions gratuites.
            Si vous avez un appareil portable sous cet OS (je rappelle en passant qu’il est autoprotégé), ne vous jetez pas sur le premier antivirus que vous trouverez, quel qu’il soit.
            Même les cleaners sont futiles, voire triviaux. Préférez les vrais utilitaires.
          </li>
        </ul>
        <h3>Les navigateurs</h3>
        <p>
          Chaque OS a développé son propre navigateur web, tous sont accessibles depuis n’importe quelle plateforme.
          Chacun a évolué en fontion des besoins et spécificités des utilisateurs et en entreprises.
        </p>
        <p>Il y a à ce jour cinq grandes plateformes de navigation:</p>
        <ol>
          <li>Firefox, développée par Mozilla (Linux)</li>
          <li>Safari (Apple)</li>
          <li>Internet Explorer et Edge (Windows)</li>
          <li>Chrome (Google)</li>
          <li>Opera</li>
        </ol>
        <p>Il en existe bien d'autres, je n'ai cité ici que les plus connus. Pour de plus amples détails, veuillez consulter les liens connexes ci-contre.<br /></p>
      </div>

    </Article>
  </div>
</Main>
