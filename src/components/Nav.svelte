<script>
  import links from "../store/links.js";
  export let segment;
  export let brand;
  export let bgColor;
</script>

<style>
  /* nav {
					border-bottom: 1px solid rgba(255,62,0,0.1);
					font-weight: 300;
					padding: 0 1em;
				}
				
				ul {
					margin: 0;
					padding: 0;
				}
				
				/* clearfix */
  /*
				ul::after {
					content: '';
					display: block;
					clear: both;
				}
				
				li {
					display: block;
					float: left;
				}
				
				[aria-current] {
					position: relative;
					display: inline-block;
				}
				
				[aria-current]::after {
					position: absolute;
					content: '';
					width: calc(100% - 1em);
					height: 2px;
					background-color: rgb(255,62,0);
					display: block;
					bottom: -1px;
				}
				
				a {
					text-decoration: none;
					padding: 1em 0.5em;
					display: block;
				} */
</style>

<div class="{bgColor}">
  <nav class="navbar container navbar-expand-lg navbar-dark {bgColor}">
    <!-- <nav class="text-uppercase"> -->

    <a class="navbar-brand" href=".">
      <!-- <img src="img/fleche verte.png" height="32" alt=""> -->
      <div class="display-5">{brand.toUpperCase()}</div>
    </a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation">
      <span class="navbar-toggler-icon" />
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto text-capitalize font-weight-300">
        {#each links as link}
          <li class="nav-item text-light">
            {#if link == 'accueil'}
              <a
                href="."
                class="nav-link {segment == undefined ? 'text-light font-weight-bold ' : ''}">{link}</a>
            {:else}
              <a
                href={link}
                class="nav-link {segment == link ? 'text-light font-weight-bold  ' : ''}">{link}</a>
            {/if}
            <!-- {link} -->
          </li>
        {/each}
        <!-- for the blog link, we're using rel=prefetch so that Sapper prefetches
						the blog data when we hover over the link or tap it on a touchscreen -->
        <!-- 
							<li><a rel=prefetch aria-current="{segment === 'blog' ? 'page' : undefined}" href="blog">blog</a></li>
						-->
      </ul>
    </div>
  </nav>
</div>
