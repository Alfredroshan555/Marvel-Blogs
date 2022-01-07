<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="Danger" class="new">
      <div class="container">
        <b-navbar-brand href="#">
          <b-img
            src="~assets/images/marvel-logo.png"
            alt=""
            fluid
            class="logo"
          />
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <!-- <b-navbar-nav>
          <b-nav-item href="#">Link</b-nav-item>
          <b-nav-item href="#" disabled>Disabled</b-nav-item>
        </b-navbar-nav> -->

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-item href="#">About</b-nav-item>
            <b-nav-item href="#">Contact</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </div>
    </b-navbar>
  </div>
</template>

<script>
export default {}
</script>

<style>
.logo {
  width: 200px;
}

.new {
  background: black;
}
</style>
