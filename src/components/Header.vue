<template>
  <div class="container mx-auto sm:flex pt-24 px-8">
    <div class="sm:w-2/5 flex">
      <img
        src="~@/assets/images/chonghui.jpg"
        class="mx-auto sm:mr-0 sm:ml-auto rounded-full"
        width="200"
        height="200"
        alt="Eli's Photo">
    </div>

    <div class="sm:w-3/5 sm:pl-12 text-center sm:text-left">
      <h1 class="font-header text-4xl mt-8">
        Elijah Goh Chong Hui
      </h1>

      <h2 class="font-sans text-xl my-4 font-normal">
        Full-stack Developer
      </h2>

      <div class="icons mt-12">
        <a href="https://www.linkedin.com/in/chonghui/">
          <LinkedIn class="icon mx-2"
            style="width: 30px;
            height: auto;" 
            viewBox="0 0 32 32" />
        </a>

        <a href="https://github.com/choonggg">
          <Github class="icon mx-2"
            style="width: 30px; height: auto;"
            viewBox="0 0 32 32" />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import LinkedIn from '@/assets/svg/linkedin2.svg'
import Github from '@/assets/svg/github.svg'

export default {
  name: 'HelloWorld',
  components: {
    LinkedIn, Github
  },
}
</script>

<style lang="scss" scoped>
.icons a {
  color: #2f2f2f;
}
</style>
