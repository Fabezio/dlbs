<script>
// import { each } from "svelte/internal";

    export let defs = []
</script>

<h3>Définitions</h3>
<ol>
    {#each defs as def}
    <li><q><em>
        {def}
        
    </em></q></li>    
    {/each}
</ol>
<p>Le sujet étant vaste, il sera exploré respectivement aux définitions.</p>    <!-- <q><em>

</em></q> -->
