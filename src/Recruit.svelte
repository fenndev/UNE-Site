<script>

  import Hero from './Hero.svelte';
</script>

<section>
        <div>
            <h3>From the depths of the <span>Pacific</span> to the edge of the <span>Galaxy</span>.</h3>
            <h4>The Terra Firma Defense Force stands ready to guard our planet and people against all threats, whether domestic or interstellar in origin.</h4>
            <p>Each Servicemember swears an oath of loyalty to the planet and all of its peoples, trascending national identity and vowing to protect sentient life wherever it may be found in the cosmos. The Terra Firm Defense Force is called to boldly go where no man has ever gone before and to shield our world from harm; will you answer the call?</p>
            <button>Enlist Now</button>
        </div>
        <img src="./assets/img/earth.jpg" alt="The Earth.">
    </section>

<style lang="scss">
    @import './style/colors.scss';
section {
    display: flex;
    background-color: black;

    img {
            width: 50%;
            height: 50%;
            align-self: center;
        }

    div {
        width: 50%;
        display: flex;
        flex-direction: column;
        padding: 2rem 8rem;

        h3, h4, p {
            color: var(--une-white);
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

        button {
            margin: 4rem 0;
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

