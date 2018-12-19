<template>

  <div>
      <br><br><br>
      <center><h1>Galeria</h1></center>
      <br>
      <hr>
      <br><br>
      <no-ssr>
    <gallery :images="images" :index="index" @close="index = null"></gallery>
    </no-ssr>
    <div
      class="image"
      v-for="(image, imageIndex) in images"
      :key="imageIndex"
      @click="index = imageIndex"
      :style="{ backgroundImage: 'url(' + image + ')', width: '300px', height: '200px' }"
    ></div>


    <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
    <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
    <br><br><br><br><br><br><br><br><br><br>
  </div>

</template>

<script>
let VueGallery = {}
if (process.browser) {
  VueGallery = require('vue-gallery')
}
  
  export default {
    data: function () {
      return {
        images: [
          '12.jpg',
          '13.jpg',
          '14.jpg',
          '15.jpg',
          '16.jpg',
          '18.jpg',
          '19.jpg',
          '20.jpg',
          '21.jpg',
          '22.jpg',
          '23.jpg',
          '24.jpg',
          '25.jpg',
          '30.jpg',
          '31.jpg',
          '32.jpg',
          '33.jpg',
          '34.jpg',
          '35.jpg',
          '36.jpg',
          '37.jpg',
          '38.jpg',
          '39.jpg',
          '40.jpg',
          '41.jpg',
          '42.jpg',
          '43.jpg',
          '44.jpg',
          '45.jpg',
          '46.jpg'
        ],
        index: null
      };
    },

    components: {
      'gallery': VueGallery
    },
  }
</script> 

<style scoped>
  .image {
    float: left;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
    border: 1px solid #ebebeb;
    margin: 5px;
  }
</style>