<template>
<div class="navbar navbar-center bg-yellow-400 md:px-10 px-1">
 <div class="navbar-start">
    <div class="dropdown">
      <label tabindex="0" class="btn btn-ghost lg:hidden">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /></svg>
      </label>
      <ul tabindex="0" class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-yellow-400 rounded-box w-52">
        <li><router-link to="/" class="link no-underline text-semibold text-yellow-900 hover:bg-yellow-900 hover:text-yellow-400">Home</router-link></li>
        <li><router-link to="/foods" class="link no-underline text-semibold text-yellow-900 hover:bg-yellow-900 hover:text-yellow-400">Foods</router-link></li>
      </ul>
    </div>
    <a class="normal-case text-xl font-bold text-yellow-900">Web-Restoran</a>
  </div>
  <div class="navbar-center hidden lg:flex">
    <ul class="menu menu-horizontal px-1">
      <li><router-link to="/" class="link no-underline text-semibold text-yellow-900 hover:bg-yellow-900 hover:text-yellow-400 mx-1">Home</router-link></li>
      <li><router-link to="/foods" class="link no-underline text-semibold text-yellow-900 hover:bg-yellow-900 hover:text-yellow-400 mx-1">Foods</router-link></li>
    </ul>
  </div>
  <div class="navbar-end mx-2">
    <router-link to="/keranjang" class="btn bg-yellow-900 hover:bg-yellow-400 hover:text-yellow-900">
      <font-awesome-icon icon="fa-cart-shopping" class="mx-auto" />
      Keranjang
      <span class="badge badge-warning mx-1 rounded-md">1</span>
    </router-link>
  </div>
</div>
</template>

<script>
export default {
    name:'Navbar'
}
</script>

<style>

</style>