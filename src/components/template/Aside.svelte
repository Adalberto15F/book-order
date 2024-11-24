<script>
    import Menu from "./Menu.svelte";
    import ItemMenu from "./ItemMenu.svelte"

</script>
<aside
    class="flex flex-col self-start
    border border-zinc-800 p-5 rounded-md gap-10 w-72"
> 
    <Menu titulo="Navegação">
        <ItemMenu texto="Inicio" link="/"/>
        <ItemMenu texto="Personagens" link="/"/>
        <ItemMenu texto="Autores" link="/"/>
        <ItemMenu texto="Séries" link="/"/>

    </Menu>
    <Menu titulo="Principais Autores">
        <ItemMenu texto="J.K. Rowling" link="/"/>
        <ItemMenu texto="J.R.R. Tolkien" link="/"/>
        <ItemMenu texto="George R.R. Martin" link="/"/>

    </Menu>
    <Menu titulo="Outras Categorias">
        <ItemMenu texto="Últimas Notícias" link="/"/>
        <ItemMenu texto="Séries Populares" link="/"/>
        <ItemMenu texto="Facebook" link="/"/>
        <ItemMenu texto="Instagram" link="/"/>
        <ItemMenu texto="Youtube" link="/"/>


    </Menu>

</aside>