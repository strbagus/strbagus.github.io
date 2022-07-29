<script setup>
// @ is an alias to /src
import HomeBanner from "@/components/Banner.vue";
import NavTop from "@/components/NavTop.vue";
import FooterCopy from "@/components/Footer.vue";
import ContactMe from "@/components/Contact.vue";
import TechStacks from "@/components/Stacks.vue";

</script>
<template>
  <div>
    <HomeBanner />
    <NavTop />
    <div class="content-box relative">
      <div class="about py-52">
        <div class="container mx-auto text-center ">
          <h2 class="text-3xl font-bold text-left mx-2 text-black">About Me |</h2>
          <div class="lg:w-1/2 mb-52">
            <h2 class="text-2xl text-red-500 mt-24 font-medium">Who I am</h2>

            <p class="mt-4 text-gray-500 text-justify mx-2">
              Hi I am bagus, i was a Software Engineering student at SMKN 1 Bantul,
              Yogyakarta, Indonesia. I interested in Web Development, i can do
              both Frontend and Backend.
            </p>
          </div>
          
          <h2 class="text-3xl font-bold text-black text-left mx-2 mb-24">Tech Stacks |</h2>
          <tech-stacks/>

          <h2 class="text-3xl font-bold text-black text-left mx-2 mt-32 mb-24">Portfolio |</h2>
          <div class="lg:w-1/2 mb-52">
            <RouterLink to="/portfolio">
              <button class="px-3 mt-3 py-1 font-medium tracking-wide text-white capitalize transition-colors duration-200 transform bg-blue-600 rounded-md hover:bg-blue-500 focus:outline-none focus:ring focus:ring-blue-300 focus:ring-opacity-80">
                  Open Portfolio
              </button>
            </RouterLink>
          </div>
        </div>
        <!-- <contact-me/> -->
      </div>
      <!-- <div class="content-inside header abosolute lg:flex text-center container mx-auto">
        <div class="lg:w-1/2 py-10 px-5">
          <h1 class="text-3xl">About Me</h1>
            <RouterLink to="/about">
              <button class="px-3 mt-3 py-1 font-medium tracking-wide text-white capitalize transition-colors duration-200 transform bg-blue-600 rounded-md hover:bg-blue-500 focus:outline-none focus:ring focus:ring-blue-300 focus:ring-opacity-80">
                More
              </button>     
            </RouterLink>
        </div>
        <div class="lg:w-1/2 py-10 px-5">
          <h1 class="text-3xl">Portfolio</h1>
            <RouterLink to="/portfolio">
              <button class="px-3 mt-3 py-1 font-medium tracking-wide text-white capitalize transition-colors duration-200 transform bg-blue-600 rounded-md hover:bg-blue-500 focus:outline-none focus:ring focus:ring-blue-300 focus:ring-opacity-80">
                  More
              </button>
            </RouterLink>
        </div>
      </div> -->
    </div>
    <ContactMe />
    <FooterCopy />
  </div>
</template>

<style>
.content-box {
  min-height: 100vh;
  background-color: rgb(237, 244, 247);
}
.content-inside{
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
}
h1{
  color: rgb(25, 25, 25);
}
</style>