<template>
    <Navbar />
    <Hero />
    <div class=" bg-slate-50 mx-8 py-4 rounded-lg mb-10">
      <div class="grid grid-cols-2 mt-6 md:px-28 px-4">
        <div class="flex justify-start">
          <h1 class="text-5xl">Best <strong>Foods</strong></h1>
        </div>
        <div class="flex justify-end">
          <button class="btn bg-yellow-900 hover:bg-yellow-400 hover:text-yellow-900">
            <router-link to="/foods">See All</router-link>
          </button>
        </div>
      </div>
        <Card />
    </div>   
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import Hero from "@/components/Hero.vue";
import Card from "@/components/Card.vue";

export default {
  name: "HomeView",
  components: {
    Navbar,
    Hero,
    Card
  },
  
};
</script>
