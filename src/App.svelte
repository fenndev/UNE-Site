<script lang="ts">
</script>

<aside>
    <div class="logo-box">
        <img src="./assets/img/une-logo.png" alt="The United Nations of Earth logo.">
        <h1>United Nations of Earth</h1>
        <h2>Terra Firma Defense Force</h2>
    </div>
</aside>
<main>
    <header>
        <h3>Serve your planet today!</h3>
        <p>Enlist with the Terra Firma Defense Force and become part of something bigger. As we reach out to the stars, we must strive to protect our home planet from all threats, foreign and domestic. The United Nations of Earth is recruiting indiviudals like you to keep our light burning bright as we venture forth into the void.</p>
    </header>
    <form action="">
        <fieldset>
            <div>
                <label for="first-name">First Name</label>
                <input type="text" placeholder="John" name="first-name">
            </div>
            <div>
                <label>Last Name</label>
                <input type="text" placeholder="Doe">
            </div>
        </fieldset>
        <fieldset>
            <div>
                <label>Email</label>
                <input type="email" placeholder="john.doe@email.com">
            </div>
            <div>
                <label>Phone Number</label>
                <input type="tel" placeholder="(123) 456-7890">
            </div>
        </fieldset>
        <fieldset>
            <div>
                <label>Password</label>
                <input type="password" placeholder="********">
            </div>
            <div>
                <label>Confirm Password</label>
                <input type="password" placeholder="********">
            </div>
        </fieldset>
        
        <button>Submit</button>
        <p>Already enlisted? <a>Log In</a></p>
    </form>
</main>

<style lang="scss">
    fieldset {
        display: flex;
        flex-direction: row;
        margin-bottom: 1rem;
        gap: 1rem;

        & > div {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }
    }
</style>