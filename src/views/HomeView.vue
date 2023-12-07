<template>
  <div class="home">
    <Hero />
    <InfoSection />
    <HeroTwo />
  </div>
</template>

<script>
import Hero from "../components/Hero.vue";
import InfoSection from "../components/InfoSection.vue";
import HeroTwo from "../components/HeroTwo.vue";

export default {
  name: "HomeView",
  components: { Hero, InfoSection, HeroTwo },
};
</script>
