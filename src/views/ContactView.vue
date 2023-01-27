<template>
  <div>
    <NavBar />
    <div class="section sec5 content" id="contact">
      <div class="main-title">
        <h2 class="text-center"><span class="a">CONTACT</span> ME</h2>
      </div>
      <template>
        <div class="contact-content-con">
          <form
            action="https://formspree.io/f/xrgvbnvv"
            method="POST"
          >
            <!-- <label>Name</label> -->
            <input
              type="text"
              v-model="name"
              name="name"
              placeholder="Your Name"
              class="box"
            />
            <!-- <label>Email</label> -->
            <input
              type="email"
              v-model="email"
              name="email"
              placeholder="Your Email"
              class="box"
            />
            <!-- <label>Message</label> -->
            <textarea
              name="message"
              v-model="message"
              cols="30"
              rows="5"
              placeholder="Message"
              class="box"
            >
            </textarea>

            <input type="submit" value="Send" />
          </form>
        </div>
      </template>
    </div>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
export default {
  components: {
    NavBar,
  },
}
</script>

<style>
.main-title h2 {
  font-size: 2rem;
}

.main-title h2 span {
  font-size: 2.5rem;
}

span {
  color: palevioletred;
}

.sec5 form {
  margin: 1rem auto;
  max-width: 50rem;
  border-radius: 5rem;
  box-shadow: 0 3px 15px rgba(0, 0, 0, 0.3);
  padding: 2rem;
}

.sec5 form .box {
  padding: 0.5rem 0.5rem;
  width: 100%;
  background: snow;
  color: black;
  /*font-size: 1.6rem;*/
  text-transform: none;
  margin: 0.1rem 0;
  /* box-shadow: 0 3px 15px rgba(0,0,0,.3); */
  border-radius: 0.5rem;
}

.sec5 form .btn {
  padding: 0.5rem 0.5rem;
  background: snow;
  color: black;
  /*font-size: 1.6rem;*/
  text-transform: none;
  margin: 0.1rem 0;
  box-shadow: 0 3px 15px rgba(0, 0, 0, 0.3);
  border-radius: 0.5rem;
}

.sec5 form textarea {
  height: 10rem;
  resize: none;
}

.sec5 form .box:focus {
  box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
  background-color: snow;
}

/* .contact-content-con {
  display: block;
  margin: auto;
  text-align: center;
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
  width: 60%;
  height: 100%;
  
} */

label {
  float: left;
}

input[type="text"],
[type="email"],
textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type="submit"] {
  background-color: #4caf50;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  text-align: center;
    display: block;
    margin: 0 auto;
}

input[type="submit"]:hover {
  background-color: #45a049;
}

</style>