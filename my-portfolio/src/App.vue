<template>
  <navbar-vue></navbar-vue>
  <router-view/>
</template>

<script>
  import NavbarVue from "./components/Navbar.vue";

  export default {
    name: 'App',
    components:{
      NavbarVue
    }
  }

</script>


<style>

</style>
