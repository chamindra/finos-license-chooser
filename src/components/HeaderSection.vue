<template>
  <header>
    <nav class="navbar">
      <div class="container">
        <div class="navbar-brand">
          <a class="icon" aria-current="page" href="/">
            <img
              src="https://www.finos.org/hs-fs/hubfs/sofin%20assets/SOFIN%20LOGOS/finos-logo.png?width=1086&name=finos-logo.png"
              alt="FinOS License chooser"
              height="40"
              width="169"
            />
          </a>
          <a
            role="button"
            aria-label="menu"
            aria-expanded="false"
            class="navbar-burger"
          >
            <span aria-hidden="true" />
            <span aria-hidden="true" />
            <span aria-hidden="true" />
          </a>
        </div>
        <div class="navbar-menu navbar-end">
         
        </div>
      </div>
    </nav>
  </header>
</template>

<script>

</script>

<style lang="scss">
#app .navbar {
  padding: 0.5rem 0 0;
}
.navbar-burger {
  background-color: white;
}
.navbar-item.navbar-item-feedback {
  font-size: 1rem;
  font-weight: bold;
  color: #787878;
  transition: color 300ms ease;
  &:hover {
    color: #fb7729;
    background-color: white;
  }
}
</style>
