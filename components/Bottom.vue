<template>
    <section>
        <v-parallax src="bottom.jpg" height="380">
          <v-layout column align-center justify-center>
            <div class="headline white--text mb-3 text-xs-center" style="background-color: rgba(0,0,0,.5);">Album "Sercem widzę więcej"</div>
            <em style="background-color: rgba(0,0,0,.5);">Debiutancki album Daniela jest już gotowy!</em>
            <br>
            <v-btn
              round color="orange"
              large
              light
              nuxt-link to="/album"
            >
              Odbierz bezpłatny album!
            </v-btn>
          </v-layout>
        </v-parallax>

        <v-container grid-list-xl>
          <v-layout row wrap justify-center class="my-5">
            <v-flex xs12 sm4>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Oferta</div>
                </v-card-title>
                <v-card-text>
                 Oprawa ślubna w kościele (Mendelsohn, Bartholdy, Giulio Caccini, Jan Sebastian Bach, Franz Schubert oraz repertuar dobierany dla każdej Młodej Pary indywidualnie).

Koncerty, festyny, koncerty kameralne itp. (Ellia Fitzgerald, Franka Sinatry, Nat King Cole, piosenki do tekstów poety Marcina Urbana, muzyka popularna i do tańca.
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm4 offset-sm1>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Kontakt</div>
                </v-card-title>
                <v-card-text>
                  Zapraszamy do współpracy.
                </v-card-text>
                <v-list class="transparent">
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="orange--text text--lighten-2">phone</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>505-721-759</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="orange--text text--lighten-2">place</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>Olsztyn, warmińsko-mazurskie</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="orange--text text--lighten-2">email</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>daniel-rupinski@wp.pl</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="orange--text text--lighten-2">face</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title><a href="https://facebook.com/daniel.rupinski" target="_blank">Facebook</a></v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                </v-list>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </section>
</template>
