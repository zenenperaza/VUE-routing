<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/services">Services</router-link> |
    <router-link to="/contact">Contact</router-link> |
    <router-link to="/blog">Blog</router-link>
  </nav>
  <router-view/>
</template>

<style lang="scss">
.router-link-exact-active{
  color: red;
}
</style>
