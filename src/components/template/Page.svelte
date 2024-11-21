<script>
    import Baseboard from "./Baseboard.svelte";
import Header from "./Header.svelte";
</script>
<div
    class="
        flex flex-col min-h-screen
        bg-black text-white
    "
>
    <Header />
    <main
        class="
            flex-1 
            
        "
    >
        <slot></slot>
    </main>
    <Baseboard />
</div>