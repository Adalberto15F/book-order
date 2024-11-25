<script>
    import {page} from "$app/stores"
    import AuthorContent from "../../../components/author/AuthorContent.svelte";
</script>

<AuthorContent autor={$page.data.autor}/>
