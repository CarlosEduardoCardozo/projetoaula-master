<script setup>
import headerComp from "./components/templete/headerComp.vue";
import RodapeComp from "./components/templete/RodapeComp.vue";
</script>
<template>
  <headerComp />
  <RouterView />
  <RodapeComp />
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  /* padding: 2rem; */
  height: 100vh;

  font-weight: normal;
}
header,
footer {
  background-image: linear-gradient(to right, rgb(50, 47, 47), rgb(61, 61, 61));
  color: rgb(255, 255, 255);
  font-size: 1.3rem;
  height: 15%;
  display: flex;
  align-items: center;
  padding-left: 2rem;
}
footer h3 {
  font-size: 1.4rem;
}
main {
  height: 70%;
}
footer .contato {
  text-align: center;
  margin: 50px;
}
</style>
