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

<main>
    <section>
        <div class='img'></div>
        <div>
            <h3>We are the future, <span>together.</span></h3>
            <p>In a historic move, the nations of Earth have agreed to form the <strong>United Nations of Earth</strong>, a supernational government body comprised of member states and tasked with ensuring the rights of all sentient beings.</p>
            <h4>Our Priorities:</h4>
            <ul>
                <li>Upholding the Constitution of Man</li>
                <li>Leading humanity to distant horizons</li>
                <li>Resolving geopolitical conflicts</li>
            </ul>
            <button>Learn More</button>
        </div>
    </section>
    <section>
        <h3>From the depths of the Pacific to the edge of the Galaxy.</h3>
        <h4>The Terra Firma Defense Force stands ready to guard our planet and people against all threats, whether domestic or interstellar in origin.</h4>
        <p>Each Servicemember swears an oath of loyalty to the planet and all of its peoples, trascending national identity and vowing to protect sentient life wherever it may be found in the cosmos. The Terra Firm Defense Force is called to boldly go where no man has ever gone before and to shield our world from harm; will you answer the call?</p>
        <button>Enlist Now</button>
    </section>
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
    }

    h1, h2, h3, h4, p, a {
        max-width: 40ch;
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

    main {

        
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

    img {
        width: 100%;
        max-width: 6rem;
        height: auto;
    }

    .img {
        width: 100%;
        height: 100%;
        background-image: url('./assets/img/une-hq.jpg');
        background-size: cover;
    }
</style>