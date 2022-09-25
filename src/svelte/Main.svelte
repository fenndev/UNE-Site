<script lang="ts" context="module">
 import Prompt from "./Prompt.svelte";
 import Form from "./Form.svelte";
</script>

<main>
    <Prompt />
    <Form />
</main>

<style lang="scss">
    main {
    height: 100%;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
}
</style>