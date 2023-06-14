<template>
  <header>
    <NavBar />
  </header>

  <HeroComponent />
  <ProdukSection />
</template>

<script>
import NavBar from "./components/NavBar.vue";
import HeroComponent from "./components/HeroComponent.vue";
import ProdukSection from "./components/ProdukSection.vue";

export default {
  name: 'App',
  components: {
    NavBar,
    HeroComponent,
    ProdukSection
},
}
</script>
