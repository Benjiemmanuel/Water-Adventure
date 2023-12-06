<template>
  <div
    class="navbar-container flex item-center justify-between pl-8 pr-8 w-full mt-0"
  >
    <div class="logo flex">
      <img class="w-20" src="../assets/clip-art-3418189_640.webp" alt="" />
      <ul>
        <li class="text-1xl font-semibold text-white">headout</li>
      </ul>
    </div>
    <div class="navbar-list-items-Left justify-center item-center">
      <ul class="flex gap-12">
        <li><a href="#">Trending</a></li>
        <li><a href="#">Headout Picks</a></li>
        <li><a href="#">Broadway</a></li>
        <li><a href="#">Recently viewed</a></li>
        <li><a href="#">More</a></li>
      </ul>
    </div>
    <div class="navbar-list-items-right">
      <ul class="flex gap-12">
        <li><i class="fas fa-search"></i></li>
        <li>Download</li>
        <li><i class="fas fa-bell"></i></li>
        <li><i class="fas fa-heart"></i></li>
        <li>Sign in</li>
        <i class="fas fa-ellipsis-vertical"></i>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
ul {
  padding-top: 15px;
  color: #9dadc2;
}
</style>
