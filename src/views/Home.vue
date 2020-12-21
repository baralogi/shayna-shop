<template>
  <div class="home">
    <Header />
    <Hero />
    <SliderItem />
    <Instagram />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Hero from "@/components/Hero.vue";
import SliderItem from "@/components/SliderItem.vue";
import Instagram from "@/components/Instagram.vue";

export default {
  name: "Home",
  components: {
    Header,
    Hero,
    SliderItem,
    Instagram,
  },
};
</script>
