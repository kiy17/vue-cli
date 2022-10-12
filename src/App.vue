<template>
  <div id="app">
    <h2>Mahasiswa Universitas Terbuka : </h2>
    <h3>Nama &ensp;: {{ nama }} </h3>
    <h3>Nim &emsp; : {{ nim }} </h3>
    <h3>UPBJJ : {{ upbjj }} </h3>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      nama: "Aggitt Dema Alfaridzi",
      nim: "041812168",
      upbjj: "Malang",
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
  border: 1px solid black;
  padding: 10px;
}
</style>
