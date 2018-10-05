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
          <i class="icon icon-linkedin-1"></i>
        </a>

        <a href="https://github.com/choonggg">
          <i class="icon icon-github"></i>
        </a>

        <a href="mailto:iamchoonggg@gmail.com">
          <i class="icon icon-mail"></i>
        </a>

      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>
