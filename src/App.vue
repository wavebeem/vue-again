<template>
  <nav>
    <router-link to="/home">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/pokedex">Pokédex</router-link>
  </nav>
  <main>
    <router-view />
  </main>
</template>

<style>
:root {
  overflow-y: scroll;
}

body {
  font-family: sans-serif;
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
  color: #42b983;
}
</style>
