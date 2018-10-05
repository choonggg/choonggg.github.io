<template>
  <section class="Contact container mx-auto px-12 sm:px-32 pt-12">
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
  </section>
</template>

<script>
export default {
  name: 'Contact',
}
</script>
