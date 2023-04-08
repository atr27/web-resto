<template>
  <div class="grid grid-cols-1 md:grid-cols-3 gap-2 mt-6">
          <div class="flex justify-center">
            <div class="card w-96 bg-base-100 border-collapse shadow-2xl mx-4">
                <figure><img src="../assets/images/nasi-ayam-geprek.jpg" alt="Ayam Geprek" /></figure>
                <div class="card-body">
                  <h2 class="card-title">Nasi Ayam Geprek</h2>
                  <p>Harga : Rp. 25.000</p>
                  <div class="card-actions justify-end">
                    <button class="btn btn-warning text-yellow-900">Buy Now</button>
                  </div>
                </div>
            </div>
          </div>
          <div class="flex justify-center">
            <div class="card w-96 bg-base-100 border-collapse shadow-2xl mx-4">
                <figure><img src="../assets/images/nasi-goreng-telor.jpg" alt="Nasi Goreng" /></figure>
                <div class="card-body">
                  <h2 class="card-title">Nasi Goreng Telor</h2>
                  <p>Harga : Rp. 15.000</p>
                  <div class="card-actions justify-end">
                    <button class="btn btn-warning text-yellow-900">Buy Now</button>
                  </div>
                </div>
            </div>
          </div>
          <div class="flex justify-center">
            <div class="card w-96 bg-base-100 border-collapse shadow-2xl mx-4">
                <figure><img src="../assets/images/mie-goreng.jpg" alt="Mie Goreng" /></figure>
                <div class="card-body">
                  <h2 class="card-title">Mie Goreng</h2>
                  <p>Harga : Rp. 20.000</p>
                  <div class="card-actions justify-end">
                    <button class="btn btn-warning text-yellow-900">Buy Now</button>
                  </div>
                </div>
            </div>
          </div>
  </div>
  
</template>

<script>
export default {
    name:'Card'
}
</script>

<style>

</style>