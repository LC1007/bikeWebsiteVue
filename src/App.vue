<template>
  <NavBar/>
  <Header/>
  <router-view/>
</template>

<script>
  import NavBar from '@/components/NavBar.vue'
  import Header from '@/components/HeaderComp.vue'

  export default{
    components: {
      NavBar,
      Header
    }
  }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: gray;
}
</style>
