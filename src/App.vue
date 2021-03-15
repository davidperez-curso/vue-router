<template>
  <div id="app" class="container">
    <h1 class="text-center my-3">Ejemplo de routing</h1>
    <div id="nav" class="text-center h5">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/servicios">Servicios</router-link> |
      <router-link to="/fotos/:id">Fotos</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#nav a {
  color: #2c3e50;
}
#nav a.router-link-exact-active {
  color: #42b983;
  text-decoration: none;
}
</style>
