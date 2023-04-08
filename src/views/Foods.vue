<template>
  <Navbar />
  <div class="grid grid-cols-1 mt-6 ml-8">
    <h2 class="text-5xl">List <strong>Foods</strong></h2>
  </div>
  <CardAllProduct />
</template>

<script>
import Navbar from '@/components/Navbar.vue';
import CardAllProduct from '@/components/CardAllProduct.vue';

export default {
 name:'Foods',
 components:{
    Navbar,
    CardAllProduct
 }
}
</script>
