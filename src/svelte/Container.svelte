<script context="module">
    import Sidebar from "./Sidebar.svelte";
    import Main from "./Main.svelte";
</script>

<div>
    <Sidebar />
    <Main />
</div>

<style lang="scss">
    div {
        height: 100%;
        width: 100%;
        display: flex;
    }
</style>