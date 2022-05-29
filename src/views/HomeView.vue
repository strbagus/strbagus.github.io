<template>
  <div>
    <HomeBanner />
    <NavTop />

    <div class="content-box py-10">
      <div class="container mx-auto">
        <h1 class="text-3xl font-bold text-left mb-5">About Me |</h1>
        <AboutMe />
        <h1 class="text-3xl font-bold text-left my-5">Portfolio |</h1>
        <PortFolio />
      </div>
    </div>
    <contact-me />
    <FooterCopy />
  </div>
</template>

<script>
// @ is an alias to /src
import HomeBanner from "@/components/Banner.vue";
import NavTop from "@/components/NavTop.vue";
import FooterCopy from "@/components/Footer.vue";
import AboutMe from "@/components/About.vue";
import PortFolio from "@/components/Portfolio.vue";
import ContactMe from "@/components/Contact.vue";

export default {
  name: "HomeView",
  components: {
    HomeBanner,
    NavTop,
    FooterCopy,
    AboutMe,
    PortFolio,
    ContactMe,
  },
};
</script>
<style>
.content-box {
  background-color: rgb(225, 239, 239);
}
</style>