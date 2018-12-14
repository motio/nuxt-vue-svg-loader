<template>
  <section class="container">
    <div>
      <logo/>
      <h1 class="title">
        nuxt-vue-svg-loader
      </h1>
      <h2 class="subtitle">
        nuxt + vue-svg-loader demo
      </h2>

      <!-- ここ -->
      <icon-twitter class="icon" />
      <icon-vue class="icon" />
      <!-- /ここ -->
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue';

import IconTwitter from '~/assets/svg/twitter.svg';
import IconVue from '~/assets/svg/vue.svg';

export default {
  components: {
    Logo,

    IconTwitter,
    IconVue,
  }
}
</script>

<style>

.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.icon {
  width: 100px;
}
</style>
