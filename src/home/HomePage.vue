<template>
  <div class="home">
    <div>
      <img src="../assets/robot-home.png" class="robot"  alt="" aria-hidden="true">
    </div>
    <div class="get-started">
      <a href="">Get started</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
