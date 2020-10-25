<script>
    import LeftSide from './Main/LeftSide.svelte';
	import Definition from './Main/Definition.svelte';
	import Article from './Main/Article.svelte';
</script>

<div class="row">

    <div class="col-md-2 col-sm-12">
        <slot name="side" />
        <!-- <LeftSide /> -->
    </div>
    <div class="col-md-10 col-sm-12">
        <slot class="mr-3   " />
        <!-- <Definition />
        <Article >
            <slot />
        </Article> -->
    </div>
</div>
