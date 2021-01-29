<template>
  <div class="home">
    <div class="main-banner">
      <img
        src="../../src/assets/main-banner.jpg"
        alt="main banner"
        class="ta-center margin-auto"
      />
    </div>
    <div class="container-1">
      <div class="right">
        <div>
          <h2 class="ta-center">Latest news</h2>
          <div>
            <ul>
            <h3>Latest and most recent streams</h3>
              <li>IMMORTALS: FENYX RISING (Being played on the PS5 on the ROAD TO 100%)</li>
              <li>DEMONS SOULS (Being played on the PS5 on the ROAD TO 100%)</li>
            </ul>
          </div>
        </div>

        <div class="img">
          <img src="../../src/assets/IMMORTALS-image.jpg" alt="" />
        </div>
      </div>
    </div>
    <!-- container 2 -->
    <div class="container-2">
      <div class="right">
        <div>
          <img src="../../src/assets/cyberpunk.jpg" alt="" />
        </div>
        <div>
          <h2 class="ta-center">Upcoming Events</h2>
            <div>
            <ul>
            <h3>Up coming streams</h3>
              <li>CYBERPUNK 2077 (Being played on the PC on the ROAD TO 100%)</li>
              <li>Check back soon for more up coming streams</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <!-- container 2 ends -->
  </div>
</template>

<script>
// @ is an alias to /src
import Main from "@/components/Main.vue";

export default {
  name: "Main",
  components: {
    Main,
  },
};
</script>


<style>
/* globals and main banner */
.home {
  font-family: "Roboto", sans-serif;
}
.ta-center {
  text-align: center;
}
.home h1 {
  text-align: center;
}
.main-banner img {
  width: 100%;
  margin-bottom: 60px;
}
/* globals and main banner ends */

/* content containers */
.container-1 {
  width: 100%;
  margin-bottom: 40px;
}
.container-1 img {
  margin-left: 40px;
}
.container-2 img {
  margin-right: 40px;
}
.container-2 {
  width: 100%;
  margin-top: 40px;
}

p {
  padding: 5px;
}
.right {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  width: 100%;
}
/* content containers ends */

/* lists */
ul {
  text-align: center;
  background: #eee;
}
ul h3 {
  padding: 5px;
}
li {
  padding: 15px;
}

@media only screen and (max-width: 600px) {
  .main-banner img {
    width: 100%;
    height: auto;
  }
  .container-1 img {
    width: 100%;
    margin: auto;
  }
   .container-2 img {
    width: 100%;
    margin: auto;
  }
  .container-2 img {
    width: 100%;
  }
  .right {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 100%;
  }
}
</style>
