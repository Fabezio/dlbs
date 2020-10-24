<script>
    export let brand = "Dans le Bon Sens"
    export let pageTitle
</script>

<svelte:head>
    <title>
        {brand} | {pageTitle}

    </title>
</svelte:head>

<header>
    <h1>{pageTitle}</h1>
</header>