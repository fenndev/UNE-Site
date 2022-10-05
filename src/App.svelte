<script>
  import Footer from './Footer.svelte';

  import Header from './Header.svelte';

  import Recruit from './Recruit.svelte';


  import Hero from './Hero.svelte';
</script>
<Header></Header>

<main>
    <Hero></Hero>
    <Recruit></Recruit>
</main>
<Footer></Footer>

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
</style>