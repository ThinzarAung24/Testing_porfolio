<template>
 
      <v-navigation-drawer
        
        app
        color="white"
        mini-variant
        mini-variant-width="90"
        permanent
        expand-on-hover
      >
        <v-list>
          <v-list-item class="px-2">
            <v-list-item-avatar>
              <v-img src="ThinzarAung.jpg"></v-img>
            </v-list-item-avatar>
          </v-list-item>

          <v-list-item link>
            <v-list-item-content>
              <v-list-item-title class="text-h6">
                Thinzar Aung
              </v-list-item-title>
              <v-list-item-subtitle
                >thinzaraung@ucsy.edu.mm</v-list-item-subtitle
              >
            </v-list-item-content>
          </v-list-item>
        </v-list>

        <v-divider></v-divider>

        <v-list nav dense>
          <v-list-item link router to="/">
            <v-list-item-icon>
              <v-icon>fa-solid fa-house-user</v-icon>
            </v-list-item-icon>
            <v-list-item-title>HOME</v-list-item-title>
          </v-list-item>
          <v-list-item link router to="/about">
            <v-list-item-icon>
              <v-icon>fa-solid fa-address-card</v-icon>
            </v-list-item-icon>
            <v-list-item-title>About</v-list-item-title>
          </v-list-item>
          <v-list-item link router to="/portfolio">
            <v-list-item-icon>
              <v-icon>fa-solid fa-heart</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Portfolio</v-list-item-title>
          </v-list-item>
          <v-list-item link router to="/contact">
            <v-list-item-icon>
              <v-icon>fa-solid fa-address-book</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Contact</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-navigation-drawer>
  
  
</template>
<script>
export default {
  //
};
</script>