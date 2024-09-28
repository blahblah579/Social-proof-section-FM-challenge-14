<template>
  <v-app>
    <v-main class="main">
      <HomePage class=""/>
    </v-main>
  </v-app>
</template>

<script setup>
import HomePage from "./components/HomePage.vue";
</script>

<style scoped>
.main {
  background-color: #ffffff;
  background-image: url("@/assets/bg-pattern-top-desktop.svg"),
    url("@/assets/bg-pattern-bottom-desktop.svg"); /* Adding both images */
  background-position: top left, bottom right; /* Positioning the images at the top-left and bottom-right */
  background-repeat: no-repeat, no-repeat; /* Prevent repeating */
  background-size: 40%, 60%; /* Adjust size of each background image */
  background-origin: content-box; /* You can adjust this if you want the origin to be the border-box, padding-box, etc. */
}
</style>