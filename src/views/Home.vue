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
        <div class="background">
          <h2 class="ta-center">Latest news</h2>
          <div>
            <h3 class="ta-center">Latest and most recent streams</h3>
              <p class="ta-center">IMMORTALS: FENYX RISING (Being played on the PS5 on the ROAD TO 100%)
                 <p class="ta-center"><a href="https://www.youtube.com/watch?v=t5EihjtPRp0&list=PLjLuYHCrULPAAS4VWnpnkIkyCIPofhBON&index=2" target="blank">Check here for the Youtube playlist</a></p>
              </p>
              <p class="ta-center">DEMONS SOULS (Being played on the PS5 on the ROAD TO 100%)
                  <p class="ta-center"><a href="https://www.youtube.com/watch?v=Iz32Be0qAYU&list=PLjLuYHCrULPB8qYrbmErzVBL6nLKaTaDc&index=1" target="blank">Check here for the Youtube playlist</a></p>
              </p>
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
        <div class="background">
          <h2 class="ta-center">Upcoming Events</h2>
            <div>
            <h3 class="ta-center">Up coming streams</h3>
              <p class="ta-center">CYBERPUNK 2077 (Being played on the PC on the ROAD TO 100%)</p>
              <p class="ta-center">Check back soon for more up coming streams</p>
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
h2 {
  font-weight: bolder;
  font-size: 2.5em;
}
h3 {
  text-decoration: underline;
}
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
  padding: 10px !important;
}
p a {
  text-decoration: none;
}
.right {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  width: 100%;
}
.background {
  background: #eee;
}
/* content containers ends */



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
