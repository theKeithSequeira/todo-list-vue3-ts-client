<template>
<Navbar />
  <div class="mt-3 container is-widescreen">
    <div class="columns">
      <div class="column is-3">
        <Sidebar />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Navbar from "@/components/Navbar.vue";
import Sidebar from "@/components/Sidebar.vue";
import { defineComponent } from "vue";
// @ is an alias to /src

export default defineComponent({
  name: "Home",
  components: {
    Sidebar,
    Navbar,
  },
});
</script>
