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
    <div class="container-3">
      <h2 class="ta-center youtube">Join the latest Playlist on Youtube!</h2>
    <div class="iframe">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/t5EihjtPRp0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    </div>

    <div class="container-4">
      <h2 class="ta-center youtube">Join the latest Stream on Twitch!</h2>
      <div class="iframe-2">
<iframe
    src="https://player.twitch.tv/?channel=therybrock&parent=localhost&muted=true"
    height="400"
    width="600"
    allowfullscreen="<allowfullscreen>">
</iframe> 
      </div>

</div>

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
  margin-bottom: 80px;
}
.container-1 img {
  margin-left: 40px;
}
.container-2 img {
  margin-right: 40px;
}
.container-2 {
  width: 100%;
  margin-top: 80px;
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

.container-3 {
  margin: auto;
  color: #000000;
  margin-top: 80px;
}
.iframe h3.youtube {
  padding: 10px;
  font-size: 2em;
  text-decoration: none;
}

.iframe {
  text-align: center;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  background: #ed3833;
  padding: 20px;
  border-radius: 10px;
  width: 100%;
  max-width: 50%;
}

.iframe-2 {
  text-align: center;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  background: #924CF7;
  padding: 20px;
  border-radius: 10px;
  width: 100%;
  max-width: 50%;
}
@media only screen and (max-width: 1024px) {
    .iframe {
    width: 100% !important;
    max-width: 100% !important;
  }
    .iframe-2 {
    width: 100% !important;
    max-width: 100% !important;
  }
  .right {
    display: block !important;
    width: 100%;
  }
  /* .container-1 img {
    margin-left: 68px;
  } */
  
  /* .container-2 img {
    margin-left: 68px;
  } */
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
  iframe {
    width: 100%;
  }
  .iframe {
    width: 100% !important;
    max-width: 80% !important;
  }
   .iframe-2{
    width: 100% !important;
    max-width: 80% !important;
  }
  .footer {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }
}

</style>
