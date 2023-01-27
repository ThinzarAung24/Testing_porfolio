<template>
  <v-app>
    <NavBar />
    <div class="news-img" :style="backgroundImageInlineStyle">
      <div class="head">

        <v-row>
          <v-col cols="4">
            <div style="position: relative" class="mt-16">
              <center>
              <!-- <h1 class="text-grey">Hello,</h1> -->
              <!-- <h1 class="text-white">I'M Thinzar Aung</h1> -->
              <h3 class="animate-charcter">Hello !! <br /> I'm <br/>Thinzar Aung</h3><br/>
              <span class="text-grey">Web Developer</span><br />

              <!-- <v-btn tile dark class="text-yellow mt-8" variant="outlined">
                Contact me
              </v-btn> -->
            </center>
            </div>
          </v-col>
          <!-- <v-col cols="1"></v-col> -->
          
          <v-col cols="8">
            <div style="position: relative; z-index: 9999" class="mt-16">
              <!-- <v-spacer><v-img class="portfolio" src="2.png" contain max-height="1500" width="900"></v-img></v-spacer> -->
              <v-spacer><v-img class="portfolio" src="2.png" contain max-height="700" width="1600"></v-img></v-spacer> 
 
            </div>
          </v-col>
        </v-row>
      </div>
    </div>
  </v-app>
</template>

<script>
import NavBar from "@/components/NavBar.vue";

export default {
  name: "Home",

  components: {
    NavBar,
  },

  computed: {
    backgroundImageInlineStyle() {
      return `background-image: url("https://cdn.vuetifyjs.com/images/parallax/material.jpg");`;
    },
  },
};
</script>

<style scoped>
.news-img {
  height: 760px;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
.head {
  position: relative;
  text-align: center;
  padding: 12px;
  margin-bottom: 6px;
  height: 400px;
  width: 100%;
  color: white;
}
.head:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 40%;
  background: rgba(68, 110, 158, 0.888);
  transform: skew(0deg, 6deg);
  text-align: center;
  
}

.animate-charcter
{
   text-transform: uppercase;
  background-image: linear-gradient(
    -225deg,
    #231557 0%,
    #44107a 29%,
    #ff1361 67%,
    #fff800 100%
  );
  background-size: auto auto;
  background-clip: border-box;
  background-size: 200% auto;
  color: #fff;
  background-clip: text;
  text-fill-color: transparent;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: textclip 3s linear infinite;
  display: inline-block;
      font-size: 50px;
}

@keyframes textclip {
  to {
    background-position: 200% center;
  }
}



</style>
