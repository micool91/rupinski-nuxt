<template>
  <div class="container">
    <br><br><br><br><br><br><br><br>
    <center><img class="model-image" src="https://image.flaticon.com/icons/svg/8/8711.svg"></center>
    <center><h1 v-if="error.statusCode === 404">Nie odnaleziono strony</h1>
    <h1 v-else>Wystąpił błąd.</h1></center>
    <center><nuxt-link to="/">Strona główna</nuxt-link></center>
    <br><br><br><br><br><br><br><br><br><br><br><br>
  </div>
</template>

<script>
export default {
  props: ['error'],
  layout: 'blog' // you can set a custom layout for the error page
}
</script>

<style>
.model-image {
  max-height: 200px;
}
</style>