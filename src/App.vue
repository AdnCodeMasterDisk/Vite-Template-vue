<template>
  <nav>
    <router-link to="/">Home</router-link>&nbsp;
    <router-link to="/about">Acerca de</router-link>
  </nav>
  <router-view />
</template>

<script>
export default {
  name: "App",
};
</script>

<style lang="sass">

  @import '@/sass/style'

  html
    text-align: center
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
    font-size: 2em
    margin-top: 20%

</style>