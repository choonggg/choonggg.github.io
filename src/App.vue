<template>
  <div id="app">
    <Header />
    <Introduction />
    <Technical />
    <History />
  </div>
</template>

<script>
import Header from './components/Header'
import Introduction from './components/Introduction'
import Technical from './components/Technical'
import History from './components/History'

export default {
  name: 'app',
  components: {
    Header,
    Introduction,
    Technical,
    History,
  }
}
</script>

<style lang="scss" src="./styles/main.scss"></style>
