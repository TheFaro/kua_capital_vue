<template>
  <div id="app">
    <HomeView />
    <StrategyView />
    <StrategistReturns />
    <InvestmentPhilosophy />
    <OurTeam />
  </div>
</template>

<script>
import HomeView from './components/desktop/Home'
import StrategyView from './components/desktop/StrategyView'
import StrategistReturns from './components/desktop/StrategistReturns'
import InvestmentPhilosophy from './components/desktop/InvestPhilosophy'
import OurTeam from './components/desktop/OurTeam'

export default {
  name: 'App',
  components: {
    HomeView,
    StrategyView,
    StrategistReturns,
    InvestmentPhilosophy,
    OurTeam,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #eee;
  padding: 0;
  margin: 0;
  overflow-x: hidden;
}


*{
  margin: 0;
}
</style>
