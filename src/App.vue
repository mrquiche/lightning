<template>
  <body>
  <div id="app" class="flexItem">
    <h1>Mr. Quiche</h1>
    <div class="searchBox">
        <pubkey-search-bar></pubkey-search-bar>
    </div>
    <h3></h3>
  </div>
  </body>
</template>

<script>

import PubkeySearchBar from "@/components/PubkeySearchBar";
export default {
  name: 'App',
  components: {PubkeySearchBar}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
