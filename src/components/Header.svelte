<script>
	// import { segment } from './../../__sapper__/dev/server/server.js';
    export let brand = "Dans le Bon Sens"
    // export let segment
    export let title
    export let header = title
    
    // export let pageTitle
</script>

<svelte:head>
    <title  >
        {brand} | {title.charAt(0).toUpperCase() + title.slice(1)}

    </title>
</svelte:head>

<header class="text-center my-4">
    <h1 class="text-uppercase">{header}</h1>
</header>