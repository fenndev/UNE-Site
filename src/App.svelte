<script>
  import Recruit from './Recruit.svelte';


  import Hero from './Hero.svelte';
</script><header>
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

<main>
    <Hero></Hero>
    <Recruit></Recruit>
</main>
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

    :global(body) {
        margin: 0;
        padding: 0;
        font-family: 'Roboto', sans-serif;

            h1, h2, h3, h4, p, a {
            max-width: 40ch;
        }
    }

    

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
    }

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
    }

    header img, footer img {
        width: 100%;
        max-width: 6rem;
        height: auto;
    }
</style>