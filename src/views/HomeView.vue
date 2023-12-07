<template>
  <div class="home">
    <Hero />
    <InfoSection />
    <HeroTwo />
    <CardCarousel />
  </div>
</template>

<script>
import Hero from "../components/Hero.vue";
import InfoSection from "../components/InfoSection.vue";
import HeroTwo from "../components/HeroTwo.vue";
import CardCarousel from "../components/CardCarousel.vue";

export default {
  name: "HomeView",
  components: { Hero, InfoSection, HeroTwo, CardCarousel },
};
</script>
