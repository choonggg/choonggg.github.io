<template>
  <section class="Section container mx-auto my-16 px-8">
    <h1 class="font-header text-2xl">{{ title }}</h1>
    <slot></slot>
  </section>
</template>

<script>
export default {
  props: {
    title: String,
    required: true
  }
}
</script>
