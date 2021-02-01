<template>
  <header class="main-header">
    <h1><span>Deply Meow's</span> Space</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit,
      explicabo.
    </p>
  </header>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

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
  color: #42b983;
}

.main-header {
  height: 55vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 2rem;
}

.main-header h1 {
  font-size: 4rem;
  margin-bottom: 2rem;
  line-height: 1.2;
}
.main-header h1 span{
  color: crimson;
}
.main-header p {
  font-size: 2rem;
}
</style>
