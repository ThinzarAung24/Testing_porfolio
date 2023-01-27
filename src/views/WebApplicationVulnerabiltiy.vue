<template>
  <div>
    <NavBar />
    <!-- <div>
    <section>
        <iframe width="642" height="361" src="https://www.youtube.com/embed/eqheeISfoWw?list=RDeqheeISfoWw" title="Chiisana Koi no Uta [Yui Aragaki] with Lyrics romanji and english sub" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </section>
  </div> -->

    <!-- <h2>CSS Template using Float</h2>
    <p>
      In this example, we have created a header, three equal columns and a
      footer. On smaller screens, the columns will stack on top of each other.
    </p>
    <p>Resize the browser window to see the responsive effect.</p> -->

    <div class="header">
      <!-- <h2>RESTAURNANT ORDER SYSTEM</h2> -->
      <div class="waviy">
        <!-- <span style="--i: 1">R</span>
        <span style="--i: 2">E</span>
        <span style="--i: 3">S</span>
        <span style="--i: 4">T</span>
        <span style="--i: 5">A</span>
        <span style="--i: 6">U</span>
        <span style="--i: 7">R</span>
        <span style="--i: 8">A</span>
        <span style="--i: 9">N</span>
        <span style="--i: 10">T</span>
        <span>_</span>
        <span style="--i: 12">O</span>
        <span style="--i: 13">R</span>
        <span style="--i: 14">D</span>
        <span style="--i: 15">E</span>
        <span style="--i: 16">R</span>
        <span style="--i: 17"></span>
        <span>_</span>
        <span style="--i: 18">S</span>
        <span style="--i: 19">E</span>
        <span style="--i: 20">R</span>
        <span style="--i: 21">V</span>
        <span style="--i: 22">I</span>
        <span style="--i: 23">C</span>
        <span style="--i: 24">E</span> -->
        <span
          >Effective Web Application Vulnerability Testing System using
          XSS_SQL_Scanning_Algorithm</span
        >
      </div>
    </div>

    <div class="row">
      <div class="column">
        <div>
          <section>
            <iframe
              width="699"
              height="393"
              src="https://www.youtube.com/embed/cNGc56SZsNE"
              title="Web Application Vulnerability Testing System Using XSS_SQL_Scanning_Algorithm"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
              allowfullscreen
            ></iframe>
          </section>
        </div>
      </div>
      <div class="column">
        <strong> * This site is used to test XSS Vulnerability for Educatioanal Purpose.* </strong><br />
        <strong><h2>Objectives</h2></strong><br/>
        To discover the possibility of web application vulnerabilities.<br/>
        To assist web developers in detecting their web applications that have weaknesses or not.<br/>
        To support the security of web application.<br/>
        To provide the basic information on how to detect SQL injection and XSS attack for some people who begin to study the web application security.

      </div>
      <!-- <div class="column" style="background-color: #ccc">Column</div> -->
    </div>

    <div class="footer">
      <p>Git Hub</p>
      <p><a href="https://github.com/ThinzarAung24/WebApplicationVulnerabilityTestingSystem-XSS-SQL-">https://github.com/ThinzarAung24/WebApplicationVulnerabilityTestingSystem-XSS-SQL-</a></p>
    </div>
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
.column {
  float: left;
  width: 50%;
  padding: 10px;
  height: 500px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

.header {
  /* background-color: #f1f1f1; */
  padding: 30px;
  text-align: center;
  font-size: 35px;
}
/* Style the footer */
.footer {
  background-color: #f1f1f1;
  padding: 10px;
  text-align: left;
}
.waviy {
  position: relative;
}
.waviy span {
  position: relative;
  display: inline-block;
  font-size: 40px;
  color: black;
  text-transform: uppercase;
  animation: flip 7s infinite;
  animation-delay: calc(0.7s * var(--i));
}
@keyframes flip {
  0%,
  80% {
    transform: rotateY(360deg);
  }
}
</style>