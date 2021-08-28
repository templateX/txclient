<template>
  <div id="nav">
    <div class="brand">
      <h2>TemplateX</h2>
    </div>
    <div class="routes">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/Dashboard">Dashboard</router-link>
      <router-link to="/Search">Search</router-link>
    </div>
  </div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.brand {
  color: #CF4D21;
}

#nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  margin: 20px 30px;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #CF4D21;
}
</style>
