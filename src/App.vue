<template>
  <div id="nav" class="app">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view />
  <div class="footer">
    <div class="container-social">
      <h3>Follow me on Social media</h3>
        <div class="icons">
      <a href="https://twitter.com/ry_brock" target="blank"><i class="fab fa-twitter"></i></a>
      <a href="https://www.instagram.com/rybrock84/" target="blank"><i class="fab fa-instagram"></i></a>
    </div>
    </div>
    <div class="container-comm">
      <h3>Join the discussions</h3>
      <div class="icons">
        <a href="https://discord.com/channels/805052463006351390/805052463006351393" target="blank"><i class="fab fa-discord"></i></a>
          <a href="https://www.twitch.tv/therybrock" target="blank"><i class="fab fa-twitch"></i></a>
          <a href="mailto:r.c_brock@yahoo.com" target="blank"><i class="fas fa-envelope-square"></i></a>

        </div>
    </div>
  
  </div>
</template>

<style>
.app {
  width: 100%;
}
/* flex styles */
.flex-item {
  margin: auto;
}
.col-12 {
  width: 100% !important;
}
/* flex styles end */

/* navbar styles */
#nav {
  margin: 20px 0 50px 0;
  text-align: center;
  font-family: "Roboto", serif;
  border-bottom: 1px solid #000000;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  background: #000000;
}

#nav a {
  text-decoration: none;
  color: #ffffff;
  margin: 20px 10px;
}
/* navbar styles end */

/* footer styles */

.footer {
  border-top: 1px solid #000000;
  font-family: "Roboto", serif;
  margin-top: 50px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-direction: row;
  background: #000000;
  color: #ffffff;
}
.container-social {
  text-align: center;
   display: flex;
  justify-content: space-around;
  align-items: center;
  flex-direction: column;
}
.container-comm {
    display: flex;
  justify-content: space-around;
  align-items: center;
  flex-direction: column;
}
.fab {
  font-size: 40px;
  padding: 10px;
}
.fas {
  font-size: 40px;
  padding: 10px;
}
.fa-twitter {
  color: #39A2F2;
}
.fa-discord {
  color: #6E85D3;
}

.icons .fa-twitch {
  font-size: 40px;

}
.fa-envelope-square {
  color: #fff;
}
</style>