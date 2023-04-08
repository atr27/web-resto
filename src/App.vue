<template>
  <div class="bg-yellow-400">
    <router-view />
    <Footer />  
  </div>
</template>

<script>
import Footer from "@/components/Footer.vue";

export default {
  name: 'App',
  components: {
    Footer
  }
}
</script>
