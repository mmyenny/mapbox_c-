<template>
  <div>
    <mapbox
      access-token="pk.eyJ1IjoiYWRyaWFudGVsbCIsImEiOiJjazNiMWF6ZDMwZWhmM25vMWNzMWwwMjc1In0.FTncNffkWs27hDOvTFkPiw"
      :map-options="{
        style: 'mapbox://styles/adriantell/ck3b3pk3x1k0e1co40bz291w7',
        center: [-96, 37.8],
        zoom: 3,
      }"
    />
  </div>
</template>

<script>
import Mapbox from "mapbox-gl-vue";

export default {
  components: { Mapbox }
};
</script>

<style>
#map {
  width: 100%;
  height: 500px;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
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
</style>
