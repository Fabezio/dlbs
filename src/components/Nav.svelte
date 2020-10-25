<script>
	export let segment;
	
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
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
<!-- <nav class="text-uppercase"> -->
	<a class="navbar-brand" href=".">DANS LE BON SENS</a>
	<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
		<span class="navbar-toggler-icon"></span>
	</button>
	<div class="collapse navbar-collapse" id="navbarSupportedContent">
		<ul class="navbar-nav mr-auto text-capitalize font-weight-300">
			
			<li class="nav-item {() => {if (segment) return 'active'}} "><a class="nav-link" aria-current="{segment === undefined ? 'page' : undefined}" href=".">Accueil</a></li>
			<li class="nav-item {() => {if (segment) return 'active'}} "><a class="nav-link" aria-current="{segment === 'civilite' ? 'page' : undefined}" href="civilite">Civilité</a></li>
			<li class="nav-item {() => {if (segment) return 'active'}} "><a class="nav-link" aria-current="{segment === 'culture' ? 'page' : undefined}" href="culture">Culture</a></li>
			<li class="nav-item {() => {if (segment) return 'active'}} "><a class="nav-link" aria-current="{segment === 'informatique' ? 'page' : undefined}" href="informatique">Informatique</a></li>
			<li class="nav-item {() => {if (segment) return 'active'}} "><a class="nav-link" aria-current="{segment === 'astronomie' ? 'page' : undefined}" href="astronomie">astronomie</a></li>
			<li class="nav-item {() => {if (segment) return 'active'}} "><a class="nav-link" aria-current="{segment === 'education' ? 'page' : undefined}" href="education">Education</a></li>
			<li class="nav-item {() => {if (segment) return 'active'}} "><a class="nav-link" aria-current="{segment === 'evolution' ? 'page' : undefined}" href="evolution">evolution</a></li>
			
			<!-- for the blog link, we're using rel=prefetch so that Sapper prefetches
					the blog data when we hover over the link or tap it on a touchscreen -->
			<!-- 
				<li><a rel=prefetch aria-current="{segment === 'blog' ? 'page' : undefined}" href="blog">blog</a></li>
			-->
				
		</ul>
	</div>
	
</nav>
