<template>
  <article class="Bluethumb">
    <div class="sm:flex mt-12">
      <div class="sm:w-2/5 mr-4">

        <h1 class="font-header text-xl">
          <a class="no-underline" href="https://bluethumb.com.au">Bluethumb</a> (Remote)
        </h1>

        <p class="text-sm">
          <em>Full Time Role</em>
          <br>
          2016 April - Current
        </p>

        <p class="content my-4 text-base">
          A marketplace for artist to publish artworks while we automate delivery and logistics so 
          they can focus on what they do best - creating art.
        </p>

        <h2 class="font-header text-lg my-2">
          Technology
        </h2>

        <p class="content my-4 text-sm">
          Bluethumb uses Ruby on Rails with bootstrap 3 + and integrated Vue with webpacker.
          PostgreSQL with a dash of Sidekiq, Redis. Hanami as micro-service.
          Testing with RSpec, Capybara, Selenium with CircleCI as CI.
          <br>
          <br>
          Migrated from Cloud66 to AWS Elastic Beanstalk
        </p>
      </div>

      <div class="sm:w-3/5">
        <a href="https://bluethumb.com.au">
          <img src="~@/assets/images/BluethumbResponsive_small.png" alt="Bluethumb Art">
        </a>

        <div class="portfolio flex justify-between items-center mt-8 px-4">
          <a href="https://rubyonrails.org/">
            <img src="https://rubyonrails.org/images/rails-logo.svg" width="90" alt="Rails">
          </a>
          <a href="https://postgresql.org">
            <img src="https://www.postgresql.org/media/img/about/press/elephant.png" width="50" alt="PostgreSQL">
          </a>
          <a href="https://stripe.com">
            <img src="https://stripe.com/img/about/logos/logos/blue@2x.png" width="80" class="mt-4" alt="stripe">
          </a>
          <a href="https://vuejs.org/">
            <img src="https://vuejs.org/images/logo.png" width="50" alt="VueJS">
          </a>
          <a href="https://getbootstrap.com">
            <img src="https://getbootstrap.com/docs/4.0/assets/brand/bootstrap-solid.svg" width="45" alt="Bootstrap">
          </a>
        </div>
      </div>

    </div>
  </article>
</template>

<script>
export default {
  name: 'Bluethumb',
}
</script>
