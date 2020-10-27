<script>
  export let segment;
  // export let links = []
  export let labels = [];
  //   $: if(segment == undefined)
</script>

<div
  class="text-uppercase vh-100 border-right border-secondary bg-light text-dark px-auto">
  <div class="text-left">
    <ul class="list-group">
      <!-- <li class="list-group-item pr-5 ">{section}</li> -->
      {#each labels as label}
        {#if label.name == 'accueil'}
          <li
            class="list-group-item {segment == undefined ? 'bg-secondary' : ''} ">
            <a href=".">{label.name}</a>
          </li>
        {:else}
          <li
            class="list-group-item  {segment == label.name ? 'bg-secondary text-light' : ''}">
            <a href={label.name}>{label.name}</a>
          </li>
        {/if}
        {#each label.sections as section}
          {#if segment == label.name || segment == section}
            {#if segment == label.name}
              <li
                class="list-group-item {segment == label.name ? 'bg-secondary' : 'bg-secondary'} ">
                <div class="ml-3 text-light">
                  <a class="text-light" href="{label.name}/{section}">
                    {section}
                  </a>
                </div>
              </li>
            {:else if segment == section}
              <li
                class="list-group-item {segment == section ? 'bg-success' : 'bg-secondary'} ">
                <div class="ml-3 ">
                  <a class="text-light" href="{label.name}/{section}">
                    {section}
                  </a>
                </div>
              </li>
            {/if}
          {/if}
        {/each}
        <div class="border-bottom border-secondary opacity-0.5" />

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
