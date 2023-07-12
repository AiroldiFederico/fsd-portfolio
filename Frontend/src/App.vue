<script setup>
import NavBarComp from "./components/NavBarComp.vue"
import CoreComp from "./components/CoreComp.vue"


</script>

<template>

  <div id="main">
    <NavBarComp/>
    <CoreComp/>
  </div>

</template>

<style lang="scss">

@use "./style/main.scss" as *;

#main {
  background-color: #f2cf8da0;
  height: 100vh !important;
}

</style>
