<template>
  <div id="nav" class="app">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view />
  <div class="footer">
    <div class="container-social">
    <h3>Follow me on Social media</h3>

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
}

#nav a {
  text-decoration: none;
  color: #000000;
  margin: 20px 10px;
}
/* navbar styles end */

/* footer styles */

.footer {
  border-top: 1px solid #000000;
}
.container-social {
  text-align: center;
}
</style>
