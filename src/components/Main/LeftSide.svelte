<script>
    export let labels = []
</script>

<div class="text-uppercase vh-100 border-right border-secondary bg-light text-dark px-auto">
    <div class="text-left">
        
        <ul class="list-group">
            {#each labels as label}
            
                <li class="list-group-item">{label}</li>
                <!-- <li class="list-group-item">Dapibus ac facilisis in</li> -->
                <!-- <li class="list-group-item">Morbi leo risus</li>
                    <li class="list-group-item">Porta ac consectetur ac</li>
                    <li class="list-group-item">Vestibulum at eros</li> -->
                    {:else}
                    <li class="list-group-item"><slot/></li>
                    <!-- <slot /> -->
                {/each}
          </ul>

    </div>
        
</div>
