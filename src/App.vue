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

    <div class="container mx-auto px-12 sm:px-32 pt-12">
      <h2 class="font-header text-center">
        I'm available for work.
      </h2>
      <h1 class="font-header text-center my-8">
        Say hi!
      </h1>
      <form action="https://formspree.io/iamchoonggg@gmail.com" method="POST">
        <input type="text" name="name" placeholder="Name">
        <input type="email" name="_replyto" placeholder="Email">
        <textarea id="" name="" cols="30" rows="10" placeholder="Message.."></textarea>
        <input type="submit" class="border border-grey rounded py-2 px-4" value="Send">
      </form>
    </div>
  </div>
</template>

<script>
import Header from './components/Header'
import Section from './components/Section'
import Introduction from './components/Introduction'

import Bluethumb from './components/portfolio/Bluethumb'
import EOasia from './components/portfolio/EOasia'
import KrispyKreme from './components/portfolio/KrispyKreme'

export default {
  name: 'app',
  components: {
    Header,
    Section,
    Introduction,
    Bluethumb,
    EOasia,
    KrispyKreme,
  }
}
</script>

<style lang="scss" src="./styles/main.scss"></style>
