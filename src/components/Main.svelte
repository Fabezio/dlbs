<script>
    import LeftSide from './Main/LeftSide.svelte';
	import Definition from './Main/Definition.svelte';
	import Article from './Main/Article.svelte';
</script>

<div class="row">

    <div class="col-md-3 col-sm-12">
        <LeftSide />
    </div>
    <div class="col-md-9 col-sm-12">
        <Definition />
        <Article >
            <slot />
        </Article>
    </div>
</div>
