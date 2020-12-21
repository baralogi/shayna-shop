<template>
  <div class="home">
    <Header />
    <Hero />
    <SliderItem />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Hero from "@/components/Hero.vue";
import SliderItem from "@/components/SliderItem.vue";

export default {
  name: "Home",
  components: {
    Header,
    Hero,
    SliderItem,
  },
};
</script>
