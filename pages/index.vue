<template>
  <div class="container">
    <Snippets />
    <nuxt-link to="skeleton">Skeletons</nuxt-link>
  </div>
</template>

<script>
import Snippets from '~/components/Snippets.vue'
export default {
  components:{Snippets}
}
</script>

<style>
  h1{
    text-align: center;
  }

  .container{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
  }
</style>
