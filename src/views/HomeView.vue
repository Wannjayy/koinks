<template>
  <div class="home">
    <AppNavbar />
  </div>
</template>

<script>
// @ is an alias to /src
import AppNavbar from "@/components/AppNavbar.vue";

export default {
  name: "HomeView",
  components: {
    AppNavbar,
  },
}
</script>
