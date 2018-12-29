<template>
  <div id="app">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
   <v-app light>
    <v-content>
      
      <Top />
      
      <nuxt />
     
      <Bottom />
      
    </v-content>
  </v-app>
 </div>
</template>

<script>
import Top from "@/components/Top";
import Bottom from "@/components/Bottom";

  export default {
    components: {
        Top, Bottom
    },
    data() {
      return {
        clipped: false,
        drawer: true,
        fixed: false,
        items: [
          { icon: 'apps', title: 'Welcome', to: '/' },
          { icon: 'bubble_chart', title: 'Inspire', to: '/inspire' }
        ],
        miniVariant: false,
        right: true,
        rightDrawer: false,
        title: 'Vuetify.js'
      }
    }
  }
</script>

<style>
html {
  font-family: "Montserrat", sans-serif;
  color: #526488;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

body,
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Montserrat", sans-serif;
  color: #886f52;
}

body,
html {
  height: 100%;
  background: #e2e1e0;
}


.card {
  background: #fff;
  border-radius: 2px;
  margin: 1rem;
  position: relative;
  padding: 30px;
  max-width: 98%;
}

.card-1 {
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
  transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
}

</style>