<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/page">Page</router-link> |
      <router-link to="/another">Another Page</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: sans-serif;
  color: #2c3e50;
  padding: 3em;
}

h1 {
  font-size: 64px;
}

#nav {
  border-bottom: 10px solid #42b983;
  padding-bottom: 30px;
  margin-bottom: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
