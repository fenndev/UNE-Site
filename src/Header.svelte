<script>
  import Recruit from './Recruit.svelte';


  import Hero from './Hero.svelte';
</script>

<header>
    <section>
        <img src="./assets/img/une-logo.png" alt="The UNE logo.">
        <h1>United Nations of Earth</h1>
        <h2>Peace, liberty, and equality for all sentient life.</h2>
    </section>
    <nav>
        <a href="/">About Us</a>
        <a href="/work">Our Work</a>
        <a href="/news">News</a>
        <a href="/get-involved">Get Involved</a>
        <a href="/enlistment">Enlistment</a>
    </nav>
</header>

<style lang="scss">
    @import './style/colors.scss';

header {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    width: 100%;

    section {
        display: flex;
        align-items: center;
        gap: 2rem;
        padding: 1rem 2rem 0 2rem;

        h2 {
            color: var(--une-dark-grey);
        }
    }

    nav {
        justify-content: flex-end;
        display: flex;
        gap: 4rem;
        padding: 1rem 2rem;
        background-color: var(--une-dark-grey);

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

