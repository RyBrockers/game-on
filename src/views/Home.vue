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
    <div class="container">
      <h2 class="ta-center">Latest news</h2>
      <div class="stage-1">
        <div class="left">
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

        <div class="right">
          <img src="https://via.placeholder.com/600x300" alt="" />
        </div>
      </div>
    </div>
    <!-- container 2 -->
    <div class="container">
      <h2 class="ta-center">Upcoming Events</h2>
      <div class="stage-2">
        <div class="right">
          <img src="https://via.placeholder.com/600x300" alt="" />
        </div>
        <div class="left">
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
/* globals */

h1 {
  font-size: 50px;
}
h2 {
  font-size: 30px;
}
.ta-center {
  text-align: center;
}

.margin-auto {
  margin: auto !important;
}

.main-banner {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 100px 0px;
}

.stage-1 {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px;
}
.stage-2 {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px;
}
.left {
  padding: 10px;
}
</style>
