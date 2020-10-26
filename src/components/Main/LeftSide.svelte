<script>
    export let segment
    // export let links = []
    export let labels = []
</script>

<div class="text-uppercase vh-100 border-right border-secondary bg-light text-dark px-auto">
    <div class="text-left">
        
        <ul class="list-group">
            <!-- <li class="list-group-item pr-5 ">{section}</li> -->
            {#each labels as label}
                <li class="list-group-item ">{label.name}</li>
                {#each label.sections as section}
                    {#if segment == label.name}
                    <li class="list-group-item {segment == section ? 'bg-success' : '' } ">
                        <div class="ml-3 bg-white">
                        {section}
                        </div>
                    </li>
                    {/if}
                    
                    
                    
                    {/each}
                    <div class="border-bottom border-secondary opacity-0.5"></div>
            

            <!-- <li class="list-group-item border-bottom border-dark {() => {(label.name == 'accueil' && segment == undefined) ||  segment  == label.name) ? 'bg-secondary text-light' : ''}} ">{label.name}</li> -->
            <!-- 
                {#if (label == "accueil" && segment == undefined) ||  segment == label}
                {:else }
                    <li class="list-group-item border-bottom border-dark">{label.name}</li>
                {/if} -->
            {/each}
        </ul>

    </div>
        
</div>
