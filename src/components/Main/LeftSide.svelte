<script>
    export let labels = []
</script>

<aside>
    <ul>
        {#each labels as label}
        <li class="text-capitalize"><a href={label}>{label}</a></li>
        {/each}
    </ul>
    <slot />
</aside>