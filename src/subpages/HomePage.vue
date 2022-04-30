<template>
  <img src="https://2slo.pl/wp-content/uploads/2021/09/Group-433.svg">
  <h1Comp msg="Witaj w lepszym planie klas pierwszych 2slo"/>
  <div>
    <a href="/#/1A">
      <button class="button1">1A</button>
    </a>
    <a href="/#/1B">
    <button class="button1">1B</button>
    </a>
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

button {
  padding: 0.8em 1.8em;
  border: 2px solid #1069AFFF;
  position: relative;
  overflow: hidden;
  background-color: transparent;
  text-align: center;
  text-transform: uppercase;
  font-size: 16px;
  transition: .3s;
  z-index: 1;
  font-family: inherit;
  color: #1069AFFF;
}

button::before {
  content: '';
  width: 0;
  height: 300%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%) rotate(45deg);
  background: #1069AFFF;
  transition: .5s ease;
  display: block;
  z-index: -1;
}

button:hover::before {
  width: 150%;
}

button:hover {
  color: #111;
}


body{
  background: #FF7800;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background: white;
  color: black;
  margin-top: 60px;
}
</style>
