<script>
  import Header from '../components/Header.svelte'
  // export let segment
  import Main from '../components/Main.svelte'
  import LeftSide from '../components/Main/LeftSide.svelte'
  import Definition from '../components/Main/Definition.svelte'
  import Article from '../components/Main/Article.svelte'

</script>

<Header title="astronomie" />
<Main>
	<div slot="side">
		<LeftSide>
      <ul>
        <li>disciplines</li>
        <li>autres</li>
      </ul>

		</LeftSide>
	</div>
	<div >
    <Definition>
      Science des astres, des corps célestes (y compris la Terre) et de la structure de l'univers.
    
    </Definition>
    <Article>
      <div slot="content">

        article à venir
      </div>

    </Article>
  </div>
</Main>


<!-- <Header pageTitle="Astronomie"></Header> -->