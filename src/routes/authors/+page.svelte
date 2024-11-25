<script>
    import AuthorItem from "../../components/author/AuthorItem.svelte";
    import Title from "../../components/shared/Title.svelte";
    import autores from "../../constants/authors";

</script>

<div class="flex flex-col gap-10">
    <Title principal="Autores" secundario="Conheça os autores que escrevem ashistórias que você ama"/>
    
    <div class="grid grid-cols-2 gap-5">
        {#each autores as autor}
            <AuthorItem {autor}/>
        {/each}
    </div>
</div>
