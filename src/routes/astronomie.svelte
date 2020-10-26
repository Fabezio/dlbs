<script>
  import Header from '../components/Header.svelte'
  export let segment
  import links from '../store/links'
  import Main from '../components/Main.svelte'
  import LeftSide from '../components/Main/LeftSide.svelte'
  import Definition from '../components/Main/Definition.svelte'
  import Article from '../components/Main/Article.svelte'
  const labels = [
    "disciplines",
    "autres"
  ]
</script>

<Main>
  <!-- <div slot="side">
    <LeftSide {labels} {links} {segment}/>
      
	</div> -->
	<div >
    <Header title="astronomie" />
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