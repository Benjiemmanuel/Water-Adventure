<template>
  <div class="sect-one">
    <NavBar />
    <div class="someText">
      <span>Home/</span>
      <span>New York/</span>
      <span>Collections/</span>
      <span>Collection Name</span>
      <div class="under-line"></div>
    </div>
    <div class="title ml-32 mt-6">
      <h1>Water Adventures <i class="fas fa-chevron-down"></i></h1>
      <p>120 Experiences in New York <i class="fas fa-chevron-down"></i></p>
    </div>
  </div>
  <div>
    <ContentPart />
  </div>
</template>

<script setup>
import NavBar from "../components/NavBar.vue";
import ContentPart from "../components/ContentPart.vue";
</script>

<style scoped>
h1 {
  font-size: 30px;
  font-weight: 600;
}
.title {
  color: #ffff;
}
.title p {
  color: #cacfd6;
}
.title .fas {
  font-size: 15px;
  margin-left: 5px;
}
.sect-one {
  background-image: url("../assets/water-ad.jpg");
  background-size: cover;
  object-fit: cover;
  height: 50vh;
}
.under-line {
  width: 325px;
  background: #9dadc2;
  height: 1.3px;
}
.someText {
  margin-top: 30px;
  margin-left: 120px;
  color: #9dadc2;
}
</style>
