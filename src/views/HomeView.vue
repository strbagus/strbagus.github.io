<template>
  <div>
    <HomeBanner />
    <NavTop />
    <div class="content-box py-48">
      <div class="header abosolute lg:flex text-center container mx-auto">
        <div class="lg:w-1/2 py-10 px-5">
          <h1 class="text-3xl">About Me</h1>
            <a href="#/about">
              <button class="px-3 mt-3 py-1 font-medium tracking-wide text-white capitalize transition-colors duration-200 transform bg-blue-600 rounded-md hover:bg-blue-500 focus:outline-none focus:ring focus:ring-blue-300 focus:ring-opacity-80">
                More
              </button>     
            </a>
        </div>
        <div class="lg:w-1/2 py-10 px-5">
          <h1 class="text-3xl">Portfolio</h1>
            <a href="#/portfolio">
              <button class="px-3 mt-3 py-1 font-medium tracking-wide text-white capitalize transition-colors duration-200 transform bg-blue-600 rounded-md hover:bg-blue-500 focus:outline-none focus:ring focus:ring-blue-300 focus:ring-opacity-80">
                  More
              </button>
            </a>
        </div>
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
import ContactMe from "@/components/Contact.vue";

export default {
  name: "HomeView",
  components: {
    HomeBanner,
    NavTop,
    FooterCopy,
    ContactMe,
  },
};
</script>
<style>
.content-box {
  background-color: rgb(237, 244, 247);
}
</style>