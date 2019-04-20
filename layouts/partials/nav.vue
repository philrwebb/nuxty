<template>
  <header>
    <nuxt-link to="/" >Nuxty</nuxt-link>
    <nav>
      <ul>
        <li> <nuxt-link to="/">Home</nuxt-link></li>
        <li> <nuxt-link to="about">About</nuxt-link></li>
        <li> <nuxt-link to="service">Services</nuxt-link></li>
        <li> <nuxt-link to="contact">Contact</nuxt-link></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {

}
</script>

<style>
    header {
      background: rgb(112, 158, 201);
      display: grid;
      grid-template-columns: repeat(2, auto);
    }
    a {
      padding: 1em 2em;
      display: block;
      text-transform: uppercase;
      text-decoration: none;
      font-weight: bold;
      color: white;
      font-size: .9em;
    }
    nav {
      justify-self: right;
    }
    ul {
      list-style-type: none;
    }
    li {
      display: inline;
    }
    li a {
      padding: 1em 2em;
      display: inline-block;
      background: rgba(0,0,0,0.1);
    }
</style>
