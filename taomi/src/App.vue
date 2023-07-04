<script setup>
import HeaderView from "./components/HeaderView.vue";
import NavBar from "./components/NavBar.vue";
import BannerView from "./components/BannerView.vue";
import FooterView from "./components/FooterView.vue";
import MainProduct from "./components/MainProduct.vue";
import MainService from "./components/MainService.vue";
import AboutUs from "./components/AboutUs.vue";
</script>

<template>
  <div>
    <header-view></header-view>
    <nav-bar></nav-bar>
    <banner-view/>
    <main-product/>
    <main-service/>
    <about-us/>
    <footer-view/>
  </div>
</template>

<style scoped>
html, body {
  height: 100%;
  padding: 0;
}
</style>