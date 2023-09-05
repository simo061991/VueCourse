<template>
  <header>
    <nav>
      <ul>
        <li class="nav-item">
          <img class="logo" alt="logo" src="./assets/build-a-bot-logo.png">
          Build a bot
        </li>
      </ul>
    </nav>
  </header>
  <main>
  <RobotBuilder/>
</main>
</template>

<script>
/* eslint-disable */ 
import RobotBuilder from './build/RobotBuilder.vue';
//import HomePage from './home/HomePage.vue';

export default {
  name: 'App',
  components: {
    RobotBuilder,
  },
};
</script>

<style>
body{
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

header {
  background-color: #999;
  width: 1084px;
  margin: 0 auto;
}
ul {
  padding: 3px;
  display: flex;
}
.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}
.logo {
  vertical-align: middle;
  height: 30px;
}
</style>
