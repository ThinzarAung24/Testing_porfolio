<template>
  <div class="about">
    <NavBar />
    <div class="main-title">
      <h2 class="text-center"><span class="a">ABOUT</span> ME</h2>
    </div>

    <v-container fluid>
      <v-row>
        <v-col cols="12" md="6">
          <div class="text-center">
            <h4 class="skill">
              MY <span class="a">INFORMATION</span>
              <p class="line">--------------------------------</p>
            </h4>
          </div>
        </v-col>
        <v-col cols="12" md="6">
          <div class="text-center">
            <h4 class="skill">
              MY <span class="a">SKILLS</span>
              <p class="line">---------------------</p>
            </h4>
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" md="6">
          <v-card class="elevation-12">
            <v-row>
              <v-col cols="12" md="7">
                <v-card-text class="mt-14">
                  <h2 class="text-center">
                    I am a Junior Developer. <br />
                    I enjoy developing software. So, I would like to do my
                    career with writing code.<br />
                    And I am interested in teaching because of enthusiastic
                    about sharing my knowledge.<br />
                    <br /><br />
                    <h5>
                      <div class="btn-container">
                        <a href="https://drive.google.com/file/d/1NuDYHunaa8soggGLwrP0P-eJDsXmtFPa/view?usp=sharing" class="down-btn">
                          <span class="btn-icon-down">
                            <i class="fas fa-download"></i>
                          </span>
                        </a>
                        <span class="btn-text-down">Download CV</span>
                      </div>
                    </h5>
                  </h2>
                </v-card-text>
              </v-col>
              <v-col cols="12" md="5">
                <v-card-text class="white--text mt-12">
                  <v-img
                    class="portfolio"
                    src="ThinzarAung-removebg.png"
                    contain
                    height="300"
                    width="1000"
                  ></v-img>
                </v-card-text>
              </v-col>
            </v-row>
          </v-card>
        </v-col>

        <v-col cols="12" md="6">
          <div class="skill-progress-bar">
            <div class="progress-bar">
              <p class="progress-title">Vue</p>
              <div class="progress-con">
                <p class="progress-text">50%</p>
                <div class="progress">
                  <span class="vue"></span>
                </div>
              </div>
            </div>
            <div class="progress-bar">
              <p class="progress-title">html</p>
              <div class="progress-con">
                <p class="progress-text">90%</p>
                <div class="progress">
                  <span class="html"></span>
                </div>
              </div>
            </div>
            <div class="progress-bar">
              <p class="progress-title">css</p>
              <div class="progress-con">
                <p class="progress-text">80%</p>
                <div class="progress">
                  <span class="css"></span>
                </div>
              </div>
            </div>
            <div class="progress-bar">
              <p class="progress-title">java script</p>
              <div class="progress-con">
                <p class="progress-text">70%</p>
                <div class="progress">
                  <span class="js"></span>
                </div>
              </div>
            </div>
            <div class="progress-bar">
              <p class="progress-title">Java</p>
              <div class="progress-con">
                <p class="progress-text">85%</p>
                <div class="progress">
                  <span class="java"></span>
                </div>
              </div>
            </div>
            <div class="progress-bar">
              <p class="progress-title">python</p>
              <div class="progress-con">
                <p class="progress-text">70%</p>
                <div class="progress">
                  <span class="python"></span>
                </div>
              </div>
            </div>
            <div class="progress-bar">
              <p class="progress-title">c#</p>
              <div class="progress-con">
                <p class="progress-text">50%</p>
                <div class="progress">
                  <span class="c"></span>
                </div>
              </div>
            </div>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
export default {
  components: {
    NavBar,
  },
};
</script>

<style>
.main-title h2 {
  font-size: 2rem;
}

.main-title h2 span {
  font-size: 2.5rem;
}

h2 {
  font-family: "Almendra", serif;
}

span {
  color: palevioletred;
}

h4 {
  margin-bottom: 5%;
  font-family: "Russo One", sans-serif;
  font-size: 1.2rem;
}

.skill-progress-bar {
  font-family: "Almendra", serif;
}

.progress-bar {
  display: flex;
  flex-direction: column;
}

.progress-title {
  text-transform: uppercase;
  color: red;
  font-weight: 500;
  display: flex;
}

.progress-con {
  display: flex;
  /* align-items: center; */
}

.progress-text {
  font-family: "Almendra", serif;
  color: green;
}

.progress {
  width: 100%;
  height: 0.45rem;
  background-color: white;
  margin-left: 1rem;
  position: relative;
}

.html {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  background-color: greenyellow;
  transition: all 0.4s ease-in-out;
  width: 90%;
}

.css {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  background-color: greenyellow;
  transition: all 0.4s ease-in-out;
  width: 80%;
}

.js {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  background-color: greenyellow;
  transition: all 0.4s ease-in-out;
  width: 70%;
}

.java {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  background-color: greenyellow;
  transition: all 0.4s ease-in-out;
  width: 85%;
}

.python {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  background-color: greenyellow;
  transition: all 0.4s ease-in-out;
  width: 70%;
}
.vue {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  background-color: greenyellow;
  transition: all 0.4s ease-in-out;
  width: 50%;
}

.c {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  background-color: greenyellow;
  transition: all 0.4s ease-in-out;
  width: 50%;
}

.btn-container {
  display: flex;
  align-self: flex-start;
  padding-top: 2rem;
}

.down-btn {
  border-radius: 30px;
  color: red;
  font-weight: 600;
  position: relative;
  display: flex;
  align-self: flex-start;
  display: flex;
  align-items: center;
  overflow: hidden;
}
.btn-text-down {
  padding: 0 1rem;
  font-weight: 600;
  position: relative;
  display: flex;
  align-self: flex-start;
  display: flex;
  align-items: center;
  overflow: hidden;
}
.btn-icon-down {
  background-color: green;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  padding: 0.5rem;
  color: white;
}

a::before {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  transform: translateX(-100%);
  transition: all 0.4s ease-out;
  z-index: -1;
}
a:hover::before {
  width: 100%;
  height: 100%;
  background-color: cyan;
  transform: translateX(0);
}
</style>
  

