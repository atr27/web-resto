<template>
        <div class="grid md:grid-cols-2 grid-cols-1 bg-yellow-400 p-6">
                <div class="flex justify-center md:order-last mb-4">
                     <img src="../assets/foods.svg"/>
                </div>
                <div class="mx-auto my-auto space-y-2 md:order-first">
                    <p class="text-6xl font-black">Delicious Food...</p>
                    <p class="text-3xl">Choose Your Order in Here</p>
                    <button class="btn bg-yellow-900 hover:bg-yellow-400 hover:text-yellow-900">
                        <router-link to="/order">Order Now</router-link>
                    </button>
                </div>   
        </div>    
</template>

<script>
export default {
    name:'Hero'
}
</script>
