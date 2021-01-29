<template>
  <div class="home">
    <h1 class="ta-center">TheRyBrock!</h1>
    <div class="main-banner">
      <img
        src="https://via.placeholder.com/1200x330"
        alt="main banner"
        class="ta-center margin-auto"
      />
    </div>
    <div class="container-1">
      <h2 class="ta-center">Latest news</h2>
      <div class="right">
        <div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ducimus
            culpa laudantium, ea tempore officia reiciendis sit neque mollitia.
            Aliquid pariatur sunt blanditiis recusandae voluptatem, distinctio
            magni officia tempora quas minima! Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Ducimus culpa laudantium, ea tempore
            officia reiciendis sit neque mollitia. Aliquid pariatur sunt
            blanditiis recusandae voluptatem, distinctio magni officia tempora
            quas minima!
          </p>
        </div>

        <div class="img">
          <img src="https://via.placeholder.com/600x300" alt="" />
        </div>
      </div>
    </div>
    <!-- container 2 -->
    <div class="container-2">
      <h2 class="ta-center">Upcoming Events</h2>
      <div class="right">
        <div>
          <img src="https://via.placeholder.com/600x300" alt="" />
        </div>
        <div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ducimus
            culpa laudantium, ea tempore officia reiciendis sit neque mollitia.
            Aliquid pariatur sunt blanditiis recusandae voluptatem, distinctio
            magni officia tempora quas minima! Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Ducimus culpa laudantium, ea tempore
            officia reiciendis sit neque mollitia. Aliquid pariatur sunt
            blanditiis recusandae voluptatem, distinctio magni officia tempora
            quas minima!
          </p>
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
.home {
  font-family: "Roboto", sans-serif;
}
.home h1 {
  text-align: center;
}
.main-banner img {
  width: 100%;
}
.container-1 {
  width: 100%;
}
.container-1 img {
  width: 100%;
}
.container-2 {
  width: 100%;
}
.container-2 img {
  width: 100%;
}
.right {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: row;
  width: 100%;
}
@media only screen and (max-width: 600px) {
 .right {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 100%;
}
}
</style>
