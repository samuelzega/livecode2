<template>
  <div id="app">
    <div id="nav">
      <router-link class="mx-5" to="/">Home</router-link>
      <router-link class="mx-5" to="/category/movie">Movie</router-link>
      <router-link class="mx-5" to="/category/series">Series</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
