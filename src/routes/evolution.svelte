<script>
  import Header from '../components/Header.svelte';
  import Main from '../components/Main.svelte'
  import LeftSide from '../components/Main/LeftSide.svelte'
  import Definition from '../components/Main/Definition.svelte'
  import Article from '../components/Main/Article.svelte'
  // export let segment
</script>
<Header title="évolution" />
<!-- <Header {segment} /> -->
<Main>
	<div slot="side">
		<LeftSide>

		</LeftSide>
	</div>
	<div >
    <Definition>
      <p>1.
Mouvement réglé de troupes.
2.
au pluriel<br>
Suite de mouvements variés.
      <!-- Science des astres, des corps célestes (y compris la Terre) et de la structure de l'univers. -->
      </p>
    
    </Definition>
    <Article>
      <div slot="content">

        article à venir
      </div>

    </Article>
  </div>
</Main>
