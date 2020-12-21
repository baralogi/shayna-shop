<template>
  <div class="home">
    <Header />
    <Hero />
    <SliderItem />
    <Instagram />
    <PartnerLogo />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Hero from "@/components/Hero.vue";
import SliderItem from "@/components/SliderItem.vue";
import Instagram from "@/components/Instagram.vue";
import PartnerLogo from "@/components/PartnerLogo.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Hero,
    SliderItem,
    Instagram,
    PartnerLogo,
    Footer,
  },
};
</script>
