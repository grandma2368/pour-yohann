<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <router-view/>
  <div class="fixed-bottom rounded opacity-3" style="background-color: #C6080A; color: blanchedalmond;">
    <router-link to="/" style="color: blanchedalmond; text-decoration: none;">Accueil</router-link> |
    <router-link to="/about" style="color: blanchedalmond; text-decoration: none;">A propos</router-link> |
    <router-link to="/gallery" style="color: blanchedalmond; text-decoration: none;">Gallerie</router-link>
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
