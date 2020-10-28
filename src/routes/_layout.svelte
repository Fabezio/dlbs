<script>
  import Nav from "../components/Nav.svelte";
  import Footer from "../components/Footer.svelte";
  export let segment;
  const bgColor = "bg-dark";
  const brand = "dans le bon sens";
  const segArr = [];
  segArr[0] = segment;
// import Header from "../components/Header.svelte";
// import Main from "../components/Main.svelte";
// import LeftSide from "../components/Main/LeftSide.svelte";
// import Definition from "../components/Main/Definition.svelte";
// import Article from "../components/Main/Article.svelte";
// import extendedLinks from "../store/links2";
// const pageTitle = segArr[0] || "Bienvenue!";
// $: if (segment == undefined) pageTitle = "Bienvenue!"
// $: console.log(pageTitle)
</script>

<Nav {segment} {bgColor} {brand} />
<div class="row ">
  <!-- <div class="col-lg-2 col-md-2 col-sm-12">
    
    <LeftSide labels={extendedLinks} {segment} />
  </div> -->
  <!-- <div class="col-lg-10 col-md-10 col-sm-12"> -->
  <div class="col-sm-12  text-justify">
		<div class="bg-light p-4 mx-auto">
			
			<slot class="" {segment} {bgColor} {brand} />
		</div>
  </div>
</div>

<Footer {bgColor} {brand} />
