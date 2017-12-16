<template>
  <div id="app">
    <h1>
      mdi vue icons
    </h1>
    <mdi-coin-icon />
    <mdi-coins-icon />
    <mdi-xbox-controller-battery-full-icon />
  </div>
</template>

<script>
import 'mdi-vue/XboxControllerBatteryFullIcon'
import 'mdi-vue/CoinsIcon'
import 'mdi-vue/CoinIcon'
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
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
