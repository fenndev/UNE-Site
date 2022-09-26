<script context="module">

</script>

<aside class="sidebar">
    <div class="logo-section">
      <div class="transparent">
        <img class="une-logo" src="./img/une-logo.png" alt="UNE Logo" />
        <h1 class="une-text">United Nations of Earth</h1>
        <h2 class="une-subtext">Terra Firma Defense Force</h2>
      </div>
    </div>
    <div class="credit-section">
      <p>Logo Courtesy of <a href="https://1000logos.net/allpng/">1000 Logos</a></p> <br>
      <p>Image Courtesy of <a href="https://unsplash.com/photos/nJI8WAqpn7Y">Unsplash</a></p>
    </div>
</aside>

<style lang="scss">
.logo-section {
  width: 100%;
  flex: 2 0 auto;
  display: flex;
  justify-content: center;
  text-align: center;
}

.une-logo {
  max-height: 200px;
  width: auto;
  margin-bottom: 2rem;
}

.une-text {
    color: var(--une-white);
    font-family: var(--une-logo-font);
    font-size: 4rem;
    font-weight: bold;
}

.une-subtext {
  color: var(--une-white);
  font-family: var(--une-logo-font);
  font-size: 2.5rem;
  font-weight: bold;
}

.transparent {
  position: absolute;
  height: 35%;
  width: 100%;
  background-color: var(--une-dark-grey-transparent);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  top: 10%;
}

/* Logo & Photo Credits */

.credit-section {
  width: 100%;
  flex: 0 1 5vh;
  text-align: center;
}

p {
  font-size: 1.4rem;
  color: var(--une-white);
  margin-bottom: .8rem;
}

a {
  color: var(--une-blue);
}

/* Sidebar */

.sidebar {
  flex: 4 0 40vw;
  position: relative;
  height: 100%;
  background: url(./img/mil-group.jpg) no-repeat;
  background-position: center;
  background-size: cover;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>