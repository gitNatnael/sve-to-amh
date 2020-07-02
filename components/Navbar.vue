<template>
  <div>
    <b-navbar type="dark" variant="dark">
      <b-navbar-nav>
        <ul class="nav-list">
          <li class="nav-item">
            <nuxt-link to="/">Index</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/test">Test</nuxt-link>
          </li>
        </ul>
      </b-navbar-nav>
    </b-navbar>
  </div>
</template>
<style scoped>
.nav-list {
  list-style: none;
  padding: 0;
  margin: 0;
}
.nav-item {
  margin: 0 10px;
}
.nav-item a {
  text-decoration: none;
  color: #fefefe;
}
.nav-item a:hover,
.nav-item a:active {
  color: #b4b4b4;
}
</style>
