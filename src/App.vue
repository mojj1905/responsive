<script setup>
import NavbarVue from "./components/Navbar.vue";
import FooterVue from "./components/Footer.vue";
import { RouterLink } from "vue-router";
</script>
<template>
  <div>
    <NavbarVue/>
    <RouterView/>
    <!-- <HomeVue/>
    <AboutVue/>
    <WhyVue/>
    <CardsVue/> -->
    <!-- <SubscribeVue/> -->
    
    <!-- <FooterVue/> -->
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
  
};
</script>

<style scoped></style>
