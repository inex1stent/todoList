<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">home</router-link> |
      <router-link to="/about">about</router-link> | 
      <router-link to="/todo">todo list</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}
#nav a {
  font-weight: bold;
  color: #2c3e50;
}
#nav a.router-link-exact-active {
  color: #3db881;
}
</style>