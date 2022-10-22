<script>
  import Search from "./components/Search.svelte";

  let search = "";
</script>

<input type="text" bind:value={search} />
<div class="center">
  {#each search as item}
    <Search {item} />
  {/each}
</div>
