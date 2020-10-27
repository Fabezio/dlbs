<script>
  export let brand;
  export let bgColor;
  const date = new Date().getFullYear();

  $: setTimeout(() => {
    return date;
  }, 1000);
</script>

<footer
  class="fixed-bottom {bgColor} w-100 text-center py-2 text-light rounded-top d-flex justify-content-center">
  {brand}
  - &copy;
  {date}
  &Tab;

  <em class="ml-2 nav-item">
    <a
      class=""
      href="http://github.com/Fabezio/dlbs.git"
      target="_blank"
      title="code source de l'auteur"
      rel="noopener noreferrer">
      code source &rsaquo;
    </a>
  </em>
</footer>

<style >
    a:hover {
		color: whitesmoke ;
    }
    /* a[title]:hover {
        padding: 10px;
        background-color: greenyellow;
        border-radius: 5px;

    } */
</style>
