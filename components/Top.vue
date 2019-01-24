<template>
    <section>
        <v-parallax src="top.jpg" height="550">
          <v-layout
            column
            align-center
            justify-center
            class="white--text"
          >
            <br><br><br><br><br>
            <br>
            <div>
            <h1 class="white--text mb-2 display-1 text-xs-center" style="background-color: rgba(0,0,0,.5); padding: 20px;">Daniel Rupiński</h1>
            <div class="subheading mb-3 text-xs-center" style="background-color: rgba(0,0,0,.5);"><i>Sercem widzę więcej</i></div>
            </div>
            
            <br><br>
            <div class="text-xs-center">
            <v-btn
              round color="orange"
              large
              light
              nuxt-link to="/"
            >
              Strona główna
            </v-btn>

            <v-btn
              round color="orange"
              large
              light
              nuxt-link to="/gallery"
            >
              Galeria
            </v-btn>

            <v-btn
              round color="orange"
              large
              light
              nuxt-link to="/concerts"
            >
              Koncerty
            </v-btn>

            <v-btn
              round color="orange"
              large
              light
              nuxt-link to="/about"
            >
              O mnie
            </v-btn>
            </div>


          </v-layout>
        </v-parallax>
      </section>
</template>
