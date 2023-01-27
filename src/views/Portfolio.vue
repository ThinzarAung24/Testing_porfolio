<template>
  <div>
    <NavBar />
    <div class="main-title">
        <h2 class="text-center">MY <span class="a">PORTFORLIO</span></h2>
    </div>
    <v-container fluid>
        <v-row>
            <v-col cols="12" md="4">

                <template>
  <v-card
    class="mx-auto"
    max-width="344"

  >
    <!-- <v-img
      src="restaurantOrder.png"
      height="200px"
    ></v-img> -->
    <div class="porfolios">
				<div class="porfolio-item">
					<div class="image-port">
						<v-img
                src="restaurantOrder.png"
                height="200px"></v-img>
						<div class="hover-item">
							<h3>Project Source</h3>
							<div class="icons">
								<div class="icon">
								<a href="https://github.com/ThinzarAung24/RestaurantOrderService-POS-system-" target="_blank" >
									<i class="fab fa-github"></i>
								</a>
							</div>
							</div>

						</div>
					</div>
				</div>
      </div>

    <v-card-title>
      Restaurant Order Service System
    </v-card-title>

    <v-card-subtitle>
      Vue JS, CSS, SPRING BOOT (JAVA)
    </v-card-subtitle>

    <v-card-actions>
      <v-btn
        color="orange lighten-2"
        to="/restaurantProject"
      
      dark
        
      >
        Read More....
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn
        icon
        @click="show1 = !show1"
      >
        <v-icon>{{ show1 ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
      </v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show1">
        <v-divider></v-divider>

        <v-card-text>
          This project is created by three Developers who are Win Mon Thi Lwin, Thinzar Aung and Kaung Linn Shann.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>
</template>
            </v-col>
            <v-col cols="12" md="4">
                <template>
  <v-card
    class="mx-auto"
    max-width="344"
  >
    <!-- <v-img
      src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
      height="200px"
    ></v-img> -->
    <div class="porfolios">
				<div class="porfolio-item">
					<div class="image-port">
						<v-img
                src="VulnerabilityTesting.png"
                height="200px"></v-img>
						<div class="hover-item">
							<h3>Project Source</h3>
							<div class="icons">
								<div class="icon">
								<a href="https://github.com/ThinzarAung24/WebApplicationVulnerabilityTestingSystem-XSS-SQL-" target="_blank" >
									<i class="fab fa-github"></i>
								</a>
							</div>
							</div>

						</div>
					</div>
				</div>
      </div>

    <v-card-title>
      Web Vulnerability Testing System
    </v-card-title>

    <v-card-subtitle>
      PYTHON
    </v-card-subtitle>

    <v-card-actions>
      <v-btn
        color="orange lighten-2"
        to="/webApplicationVulnerabiltiyTesting"
        dark
      >
        READ MORE....
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn
        icon
        @click="show2 = !show2"
      >
        <v-icon>{{ show2 ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
      </v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show2">
        <v-divider></v-divider>

        <v-card-text>
          This is my Master Degree's Thesis Project.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>
</template>
            </v-col>
            <v-col cols="12" md="4">
                <template>
  <v-card
    class="mx-auto"
    max-width="344"
  >
    <v-img
      src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
      height="200px"
    ></v-img>

    <v-card-title>
      Top western road trips
    </v-card-title>

    <v-card-subtitle>
      1,000 miles of wonder
    </v-card-subtitle>

    <v-card-actions>
      <v-btn
        color="orange lighten-2"
        text
      >
        Explore
      </v-btn>

      <v-spacer></v-spacer>

      <v-btn
        icon
        @click="show3 = !show3"
      >
        <v-icon>{{ show3 ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
      </v-btn>
    </v-card-actions>

    <v-expand-transition>
      <div v-show="show3">
        <v-divider></v-divider>

        <v-card-text>
          I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
        </v-card-text>
      </div>
    </v-expand-transition>
  </v-card>
</template>
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
  data: () => ({
      show1: false,
      show2: false,
      show3: false,
    }),
};
</script>

<style>
span {
  color: palevioletred;
}

.main-title h2 {
  font-size: 2rem;
}

/* .port-text{
	padding: 2rem 0;
	text-align: center;
	color: chartreuse;
} */

/* .porfolios{
	display: grid;
	grid-template-columns: repeat(2, 1fr);
	grid-gap: 3rem;
	margin-top: 2rem;
} */
 .porfolio-item{
	position: relative;
	border-radius: 15px;
}

.image-port img{
	width: 100%;
	height: 200px;
	object-fit: cover;
	border-radius: 15px;
}

.image-port .hover-item{
	width: 100%;
	height: 200px;
	background-color: white;
	position: absolute;
	left: 0;
	top: 0;
	border-radius: 15px;
	display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
	opacity: 0;
	transform: scale(0);
	transition: all .4s ease-in-out;
}

.image-port .hover-item h3{
	font-size: 1.5rem;
	color:black;
	margin-bottom: 1.5rem;
}

.porfolio-item:hover .hover-item {
	opacity: 1;
	transform: scale(1);
}



.porfolios .icons{
	display: flex;
	justify-content: center;
	align-items: center;

}

.porfolios .icon{
	display: flex;
	justify-content:center ;
	width: 50px;
	height: 50px;
	align-items: center;
	margin: 0 1rem;
	cursor: pointer;
	transition: all .4s ease-in-out;
	border-radius: 50%;

}

.porfolios i{
	font-size: 1.5rem;
	color: black;
	margin: 0 2rem;
} 


</style>