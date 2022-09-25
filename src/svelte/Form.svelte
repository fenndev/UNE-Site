<script lang="ts">
    import FormBody from "./form/Form-Body.svelte";
    import FormTitle from "./form/Form-Title.svelte";
    import FormFooter from "./form/Form-Footer.svelte";
</script>

<form class="sign-up" id="sign-up" action="#" method="post">
    <div class="form-margin">
        <FormTitle />
        <FormBody />
        <FormFooter />  
    </div>
</form>

<style lang="scss">
    @import "../style/common.scss";
    form {
        background-color: var(--une-white);
    }
</style>