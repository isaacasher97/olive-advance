<template>
  <div class="home">
    <Hero />
    <InfoSection />
  </div>
</template>

<script>
import Hero from "../components/Hero.vue";
import InfoSection from "../components/InfoSection.vue";

export default {
  name: "HomeView",
  components: { Hero, InfoSection },
};
</script>
