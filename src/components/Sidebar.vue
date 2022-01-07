<template>
  <aside class="menu">
  <p class="menu-label is-size-6 has-text-weight-bold">
    Media Tracker
  </p>
  
  <p class="menu-label is-size-7">
Media Types
  </p>
  <ul class="menu-list">
  
    <li><a href="">Movies</a></li>
    <li><a href="">TV Shows</a></li>
    <li><a href="">Podcasts</a></li>
    <li><a href="">Books</a></li>
    <li><a href="">Audiobooks</a></li>
    <li><a href="">Songs</a></li>
  </ul>
  
</aside>
</template>

<script lang="ts">
import { defineComponent } from "vue";
// @ is an alias to /src

export default defineComponent({
  name: "Sidebar",
  components: {

  },
});
</script>