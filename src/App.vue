<template>
  <div id="app">
    <Header />

    <Section title="Hi! I am Elijah Goh, but you can call me Eli.">
      <Introduction />
    </Section>

    <Section title="Portfolio">
      <Bluethumb />
      <EOasia class="pt-12" />
      <KrispyKreme class="pt-16" />
    </Section>

    <Contact />

  </div>
</template>

<script>
import Header from './components/Header'
import Section from './components/Section'
import Introduction from './components/Introduction'

import Bluethumb from './components/portfolio/Bluethumb'
import EOasia from './components/portfolio/EOasia'
import KrispyKreme from './components/portfolio/KrispyKreme'

import Contact from './components/Contact'

export default {
  name: 'app',
  components: {
    Header,
    Section,
    Introduction,
    Bluethumb,
    EOasia,
    KrispyKreme,
    Contact,
  }
}
</script>

<style lang="scss" src="./styles/main.scss"></style>
