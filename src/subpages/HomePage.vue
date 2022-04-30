<template>
  <img src="https://2slo.pl/wp-content/uploads/2021/09/Group-433.svg">
  <h1Comp msg="Welcome to 2slo lesson plan"/>
  <div class="chooser">
    <button class="chooser button" @click="goTo1A()">1A</button>
    <button class="chooser button" >1B</button>
  </div>
</template>
<script>
import H1Comp from "@/components/h1Comp";

export default {
  name: "HomePage",
  components: {H1Comp}
}
</script>

<style>
.chooser{

}
.chooser button{
  margin: 1%;
  padding: 6px 30px;
}

body{
  background: #FF7800;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
  background: white;
  margin-top: 60px;
}
</style>
