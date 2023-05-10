<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <router-view/>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Saira+Stencil+One&display=swap');
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center; */
  background: linear-gradient(45deg, #ff3191, #ffaac3);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-size: 50px;
  font-family: 'Saira Stencil One', sans-serif;
  text-align: center;
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
