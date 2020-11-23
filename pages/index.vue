<template>
  <div>
    <section class="hero is-light">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">Hero title</h1>
          <h2 class="subtitle">Hero subtitle</h2>
        </div>
      </div>
    </section>

    <nav
      class="navbar is-danger"
      role="navigation"
      aria-label="main navigation"
    >
      <div class="container">
        <div class="navbar-brand">
          <a
            role="button"
            class="navbar-burger burger"
            aria-label="menu"
            aria-expanded="false"
            data-target="navbarBasicExample"
          >
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>

        <div id="navbarBasicExample" class="navbar-menu">
          <div class="navbar-start">
            <a class="navbar-item"> Home </a>

            <a class="navbar-item"> Documentation </a>

            <div class="navbar-item has-dropdown is-hoverable">
              <a class="navbar-link"> More </a>

              <div class="navbar-dropdown">
                <a class="navbar-item"> About </a>
                <a class="navbar-item"> Jobs </a>
                <a class="navbar-item"> Contact </a>
                <hr class="navbar-divider" />
                <a class="navbar-item"> Report an issue </a>
              </div>
            </div>
          </div>

          <div class="navbar-end">
            <div class="navbar-item">
              <div class="buttons">
                <a class="button is-primary">
                  <strong>Sign up</strong>
                </a>
                <a class="button is-light"> Log in </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>

    <section class="section">
      <div class="container">
        <div class="columns">
          <div class="column mr-5 box">First column - sidebar</div>
          <div class="column is-9 box">Second column - main content</div>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container">
        <h1 class="title">Section - 2</h1>
        <h2 class="subtitle">
          A simple container to divide your page into <strong>sections</strong>,
          like the one you're currently reading
        </h2>
      </div>
    </section>

    <section class="section">
      <div class="container">
        <div class="tile is-ancestor">
          <div class="tile is-4 is-vertical is-parent">
            <div class="tile is-child box"><p class="title">One</p></div>
            <div class="tile is-child box"><p class="title">Two</p></div>
          </div>
          <div class="tile is-parent">
            <div class="tile is-child box">
              <p class="title">Three</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!--Tiles-->
    <section class="section">
      <div class="container">
        <div class="tile is-ancestor">
          <!-- first column -->
          <div class="tile is-8 is-vertical">
            <!--Our imagined subtile-->
            <div class="tile">
              <div class="tile is-vertical is-parent">
                <div class="tile is-child box">
                  <p class="title">Vertical...</p>
                </div>
                <div class="tile is-child box">
                  <p class="title">...tiles</p>
                </div>
              </div>
              <div class="tile is-parent">
                <div class="tile is-child box">
                  <p class="title">Middle tile</p>
                </div>
              </div>
            </div>
            <div class="tile is-parent">
              <!--The bottom tile in the first column-->
              <div class="tile is-child box">
                <p class="title">Wide title</p>
              </div>
            </div>
          </div>
          <div class="tile is-parent">
            <!-- second column -->
            <div class="tile is-child box">
              <p class="title">Tall tile</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          <strong>Bulma</strong> by
          <a href="https://jgthms.com">Jeremy Thomas</a>. The source code is
          licensed
          <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The
          website content is licensed
          <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/"
            >CC BY NC SA 4.0</a
          >.
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
@import 'assets/scss/main';
</style>
