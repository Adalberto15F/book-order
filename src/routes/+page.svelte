<script>
    import SerieItem from "../components/serie/SerieItem.svelte";
import series from "../constants/series";
</script>

<div class="flex flex-col gap-5">
    {#each series as serie }
        <SerieItem {serie} />
    {/each}
</div>
