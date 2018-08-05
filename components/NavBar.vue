<template>
  <b-navbar toggleable="md" type="dark" variant="dark">

    <b-navbar-toggle target="nav_collapse"/>

    <b-navbar-brand to="/" class="mr-5">Home</b-navbar-brand>

    <b-collapse id="nav_collapse" is-nav >

      <b-navbar-nav>
        <!-- <nuxt-link to="/about">About Us</nuxt-link> -->
        <b-nav-item to="/about">About Us</b-nav-item>
        <b-nav-item to="/church">Church</b-nav-item>
        <b-nav-item to="/school">School</b-nav-item>
        <b-nav-item to="/earlylearningcenter">Early Learning Center</b-nav-item>
        <b-nav-item to="/newsandevents">News and Events</b-nav-item>
      </b-navbar-nav>

    </b-collapse>
  </b-navbar>

<!-- navbar-1.vue -->
</template>

<script>
export default {}
</script>
