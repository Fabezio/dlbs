<script>
	// import { segment } from './../../__sapper__/dev/server/server.js';
    export let brand = "Dans le Bon Sens"
    export let segment = ""
</script>

<svelte:head>
    <title >
        {brand} | {segment}

    </title>
</svelte:head>

<header class="text-center my-4">
    <h1 class="text-uppercase">{segment}</h1>
</header>