<section class='hero'>
        <img src="./assets/img/une-hq.jpg" alt="The United Nations">
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

<style lang="scss">
    @import './style/colors.scss';

section {
    display: flex;

    div {
        display: flex;
        flex-direction: column;
        padding: 2rem 8rem;

        h3, h4, p {
            color: var(--une-dark-grey);
        }

        h3 {
            font-size: 4rem;

            span {
                color: var(--une-blue);
            }
        }

        p {
            font-size: 2.5rem;
        }

        h4 {
            font-size: 3rem;
        }

        li {
            color: var(--une-dark-grey);
            font-size: 2.5rem;
        }

        button {
            margin-top: 4rem;
            width: 24rem;
            height: 6rem;
            background-color: var(--une-blue);
            color: var(--une-white);
            border: none;
            font-size: 3rem;
            align-self: flex-end;
        }
    }
}
</style>

