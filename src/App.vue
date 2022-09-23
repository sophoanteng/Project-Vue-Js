<template>
  <div id="app">
    <div class="container">
      <nav>
        <router-link to="/" class="title">UIFrondEnd </router-link>
        <router-link to="/product" class="menu-1">Products</router-link>
        <router-link to="/about" class="menu-2">Company</router-link>
        <router-link to="/connect" class="menu-3">Connect</router-link>
      </nav>
      <div class="button-log">
        <button type="submit" class="btn-login">Login</button>
        <button type="submit" class="btn-sign">Sign Up</button>
      </div>
      <h1 class="title-show">A modern publishing platform</h1>
      <p class="subTitle-show">Grow your audience and build your online brand</p>
      <div class="button-show">
          <button type="submit" class="btn-more">Show More Info</button>
          <button type="submit" class="btn-info">See Other Style</button>
        </div>
      <!-- <img class="banner_1" src="./assets/banner_1.svg" alt=""> -->
    </div>
    <router-view/>
  </div>
</template>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
nav a.router-link-exact-active[data-v-7ba5bd90] {
    color: #ffff;
}
.title-show{
  color: white;
  margin-top: 7%;
  font-size: 50px;
}
.button-show {
  margin-top: 30px;
}
.subTitle-show {
  color: white;
  margin-top: -23px;
}
.button-log{
  text-align: end;
  margin-top: -2%;
  position: relative;
  margin-right: 2%;
}
.btn-more{
  width: auto;
  padding: 15px;
  border-radius: 16px;
  border: none;
  cursor: pointer;
  color: #FF876E;
}
.btn-login{
  width: 80px;
  padding: 10px;
  border-radius: 16px;
  border: none;
  cursor: pointer;
}
.btn-sign{
  margin-left: 1%;
  width: 90px;
  padding: 10px;
  border-radius: 16px;
  border: none;
  cursor: pointer;
}
.btn-info{
  margin-left: 1%;
  width: auto;
  padding: 15px;
  color: white;
  background: none;
  border: 1px solid white;
  border-radius: 16px;
  cursor: pointer;
}
.menu-1 {
  margin-left: 7%;
  padding-right: 25px;
  color: white;
  text-decoration: none;
  cursor: pointer;
}
.menu-2 {
  padding-right: 25px; 
  color: white;
  text-decoration: none;
  cursor: pointer;
}
.menu-3 {
  color: white;
  text-decoration: none;
  cursor: pointer;
}
.title{
  text-align: start;
  color: white;
  font-size: 40px;
  text-decoration: none;
  cursor: pointer;
}
.banner_1{
  width: 143vh;
    top: -19%;
    right: 12%;
    position: absolute;
    display: flex;
}
.container {
  width: 100%;
  height: 600px;
  background: #FF876E;
  margin: 0;
  border-bottom-left-radius: 150px;
}
nav {
  padding: 30px;
  text-align: start;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
