<script lang="ts">
    import { fromStore } from 'svelte/store';
	import '../app.css';
	import Page from "../components/template/Page.svelte";
	let { children } = $props();
</script>

	<Page>
		{@render children()}
	</Page>


