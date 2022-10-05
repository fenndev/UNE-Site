<script>
  import Header from './Header.svelte';

  import Recruit from './Recruit.svelte';


  import Hero from './Hero.svelte';
</script>

<footer>
    <div>
        <img src="./assets/img/une-logo.png" alt="The UNE logo.">
        <h3>United Nations of Earth</h3>
    </div>
    <nav>
        <a href="/index">Site Index</a>
        <a href="/contact">Contact</a>
        <a href="/copyright">Copyright</a>
        <a href="/faq">FAQ</a>
        <a href="/privacy">Privacy</a>
    </nav>
</footer>

<style lang="scss">
    @import './style/colors.scss';

footer {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    width: 100%;
    background-color: var(--une-dark-grey);
    border-top: 4px solid var(--une-blue);

    div {
        display: flex;
        align-items: center;
        gap: 2rem;
        padding: 1rem 2rem 0 2rem;

        h3 {
            color: var(--une-white);
        }
    }

    nav {
        justify-content: flex-end;
        display: flex;
        gap: 4rem;
        padding: 1rem 2rem;

        a {
            color: var(--une-white);
            text-decoration: none;
            font-size: 1.25rem;
        }
    }

    img {
    width: 100%;
    max-width: 6rem;
    height: auto;
}
}


</style>

