<template>
  <div id="main-container">
    <div id="nav">
      <router-link to="/">Home</router-link>|
      <router-link to="/dice">dice</router-link>|
      <router-link to="/mine">mine</router-link>
    </div>
    <div id="subapp-container"></div>
    <router-view />
  </div>
</template>

<style lang="scss">
#container {
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
