<template>
  <div class="100vh">
    <Header />
    <Footer-comp />
  </div>
</template>


<script setup>
import Header from "components/Header.vue";
import FooterComp from "components/FooterComp.vue";
defineOptions({
  name: "MainPage",
});
</script>

