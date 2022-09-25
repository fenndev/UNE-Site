<div>
    <button type="submit" form="sign-up">Enlist</button>
    <p>Already enlisted? <a href="#">Log In</a></p>
</div>

<style lang="scss">

    div {
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        width: 50%;
        margin-top: 2rem;
        margin-bottom: 2rem;
    }

    button {
        width: 15rem;
        height: 5rem;
        border: none;
        border-radius: .8rem;
        background-color: var(--une-blue);
        box-shadow: .1rem .1rem var(--une-dark-grey);
        cursor: pointer;
        color: var(--une-white);
        font-family: var(--une-logo-font);
        font-size: 2rem;
        font-weight: bold;
    }

    p {
        font-size: 1.6rem;
        margin-top: 1rem;
        margin-left: 0.5rem;
    }

    a {
    color: var(--une-blue);
    }
</style>