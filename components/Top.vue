<template>
    <section>
        <v-parallax src="top.jpg" height="550">
          <v-layout
            column
            align-center
            justify-center
            class="white--text"
          >
            <img src="~/assets/trumpet.svg" alt="Daniel Rupiński" height="200">
            <br>
            <h1 class="white--text mb-2 display-1 text-xs-center" style="background-color: rgba(0,0,0,.5);">Daniel Rupiński</h1>
            <div class="subheading mb-3 text-xs-center" style="background-color: rgba(0,0,0,.5);"><i>trąbka, pianino, akordeon</i></div>
            
            <br><br>
            <div class="text-xs-center">
            <v-btn
              round color="orange"
              large
              light
              href="/"
            >
              Strona główna
            </v-btn>

            <v-btn
              round color="orange"
              large
              light
              href="/gallery"
            >
              Galeria
            </v-btn>

            <v-btn
              round color="orange"
              large
              light
              href="/music"
            >
              Muzyka
            </v-btn>

            <v-btn
              round color="orange"
              large
              light
              href="/about"
            >
              O mnie
            </v-btn>
            </div>


          </v-layout>
        </v-parallax>
      </section>
</template>
