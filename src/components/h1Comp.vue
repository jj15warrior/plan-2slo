<template>
  <div class="component1">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'h1Comp',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div {
  margin: 40px 0 0;
}
h1 {
  list-style-type: none;
  padding: 0;
  font-family: "Ubuntu Condensed";
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
