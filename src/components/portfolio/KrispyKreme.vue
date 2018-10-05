<template>
  <article class="KrispyKreme">
    <div class="sm:flex mt-12 sm:px-12">

      <div class="sm:w-1/2 mr-4">
        <h1 class="font-header text-xl">
          <a class="no-underline" href="http://krispykreme.sg/">Krispy Kreme Singapore</a>
          <br>
          (Nokomai Studios)
        </h1>

        <p class="text-sm">
          <em>Full Time Role</em>
          <br>
          2013 August
        </p>

        <p class="content my-4 text-base">
          Few projects under my belt during my time in Nokomai Studios, 
          Krispy Kreme was the most notable. Built in 2013, still standing today.
        </p>

        <h2 class="font-header text-lg my-2">
          Technology
        </h2>

        <p class="content my-4 text-sm">
          Krispy Kreme uses Wordpress, jQuery and early SCSS with Compass to compile.
          No CSS framework used, purist used to be cool.
        </p>
      </div>

      <div class="sm:w-1/2">
        <a href="https://bluethumb.com.au">
          <img src="~@/assets/images/KKreme_small.png" alt="Krispy Kreme Donuts">
        </a>
      </div>

    </div>

    <div class="portfolio flex justify-center items-center mt-4 px-4">
      <a href="https://wordpress.org/" class="inline-block mr-24">
        <img src="https://s.w.org/style/images/wporg-logo.svg?3" width="250" alt="Wordpress">
      </a>
      <a href="https://postgresql.org">
        <img src="https://sass-lang.com/assets/img/logos/logo-b6e1ef6e.svg" width="100" alt="SASS">
      </a>
    </div>

  </article>
</template>

<script>
export default {
  name: 'KrispyKreme',
}
</script>
