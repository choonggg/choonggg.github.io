<template>
  <article class="EOasia">
    <div class="sm:flex sm:flex-row-reverse mt-12">

      <div class="sm:w-2/5">
        <h1 class="font-header text-xl">
          <a class="no-underline" href="http://eoasia.com">eOasia</a> (Tinkerbox Studios)
        </h1>

        <p class="text-sm">
          <em>Full Time Role</em>
          <br>
          2016 December
        </p>

        <p class="content my-4 text-base">
          Online booking platform for your travel needs around Asia. Book activities and rides from select destinations.
        </p>

        <h2 class="font-header text-lg my-2">
          Technology
        </h2>

        <p class="content my-4 text-sm">
          eOasia deploys
          Krispy Kreme uses Wordpress, jQuery and early SCSS with Compass to compile.
        </p>
      </div>

      <div class="sm:w-3/5 sm:mr-12">
        <a href="https://bluethumb.com.au">
          <img src="~@/assets/images/eoasia_small.png" alt="eOasia">
        </a>
      </div>

    </div>

    <div class="portfolio flex justify-between items-center mt-8 sm:px-24">
      <img src="https://rubyonrails.org/images/rails-logo.svg" width="90" alt="Rails">
      <img src="https://www.postgresql.org/media/img/about/press/elephant.png" width="40" alt="PostgreSQL">
      <img src="https://jquery.com/jquery-wp-content/themes/jquery/images/logo-jquery@2x.png" width="100" alt="jQuery" class="jquery p-4">
      <img src="https://getbootstrap.com/docs/4.0/assets/brand/bootstrap-solid.svg" width="35" alt="Bootstrap">
      <img src="~@/assets/images/brands/heroku.png" width="120" alt="">
    </div>

  </article>
</template>

<script>
export default {
  name: 'EOAsia',
}
</script>

<style>
.jquery {
  background: #0768AD
}
</style>
