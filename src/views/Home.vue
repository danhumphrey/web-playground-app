<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Home msg="Welcome to the Web Playground" />
  </div>
</template>

<script>
// @ is an alias to /src
import Home from "@/components/Home.vue";

export default {
  name: "Home",
  components: {
    Home
  }
};
</script>
