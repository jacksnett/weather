<template>
  <nav
    class="navbar"
    role="navigation"
    aria-label="main navigation"
    dir="rtl"
    lang="he"
  >
    <div class="navbar-brand">
      <a
        role="button"
        class="navbar-burger"
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
      <div class="navbar-end">
        <a class="navbar-item"> Home </a>
        <a class="navbar-item"> Documentation </a>
      </div>

      <div class="navbar-item">
        <h1>dadada</h1>
        <i class="fas fa-cloud fa-2x mdi mdi-light"></i>
      </div>

      <div class="navbar-start">
        <div class="navbar-item">
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
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>