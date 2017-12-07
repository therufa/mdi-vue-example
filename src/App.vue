<template>
  <div id="app">
    <div>
      mdi vue icons
    </div>
    <mdi-coin-icon />
    <coins-icon />
    <mdi-xbox-controller-battery-full-icon />
  </div>
</template>

<script>
import 'mdi-vue/XboxControllerBatteryFullIcon'
import CoinIcon from 'mdi-vue/CoinIcon'
import 'mdi-vue/CoinsIcon'

export default {
  name: 'app',
  component: {
    CoinIcon,
  }
}
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
