<script>
  import Nav from "../components/Nav.svelte";
  import Header from "../components/Header.svelte";
  import Main from "../components/Main.svelte";
  import LeftSide from "../components/Main/LeftSide.svelte";
  import Definition from "../components/Main/Definition.svelte";
  import Article from "../components/Main/Article.svelte";
  import Footer from "../components/Footer.svelte";
  import extendedLinks from "../store/links2";
  export let segment;
  const bgColor = "bg-dark";
  const brand = "dans le bon sens";
  const segArr = [];
  const pageTitle = segArr[0] || "Bienvenue!";
  segArr[0] = segment;
  // $: if (segment == undefined) pageTitle = "Bienvenue!"
  // $: console.log(pageTitle)
</script>

<Nav {segment} {bgColor} {brand} />
<div class="row ">
  <!-- <div class="col-lg-2 col-md-2 col-sm-12">
    
    <LeftSide labels={extendedLinks} {segment} />
  </div> -->
  <!-- <div class="col-lg-10 col-md-10 col-sm-12"> -->
  <div class="container text-justify">
    <slot class=" m-0 p-3 " {segment} {bgColor} {brand} />
  </div>
</div>

<Footer {bgColor} {brand} />
