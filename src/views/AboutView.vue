<template>
  <div class="about">
    <nav-top />
    <a href="#/">
    <button class="flex m-2 items-center px-2 py-2 font-medium tracking-wide capitalize transition-colors duration-200 transform text-gray-500 hover:text-white rounded-md hover:bg-blue-600 focus:outline-none focus:ring focus:ring-blue-300 focus:ring-opacity-80">
        <svg class="w-5 h-5 mx-1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
            <path fill-rule="evenodd" d="M4 2a1 1 0 011 1v2.101a7.002 7.002 0 0111.601 2.566 1 1 0 11-1.885.666A5.002 5.002 0 005.999 7H9a1 1 0 010 2H4a1 1 0 01-1-1V3a1 1 0 011-1zm.008 9.057a1 1 0 011.276.61A5.002 5.002 0 0014.001 13H11a1 1 0 110-2h5a1 1 0 011 1v5a1 1 0 11-2 0v-2.101a7.002 7.002 0 01-11.601-2.566 1 1 0 01.61-1.276z" clip-rule="evenodd" />
        </svg>
        <span class="mx-1">Back</span>
    </button>
    </a>
    
      <div class="container mx-auto text-center py-52">
        <h2 class="text-3xl font-bold text-left mx-2">About Me |</h2>
        <div class="lg:w-1/2">
          <h2 class="text-3xl font-bold text-gray-800 mt-24">Who I am</h2>

          <p class="mt-4 text-gray-500 text-justify mx-2">
            Hi I am bagus, i was a Software Engineering student at SMKN 1 Bantul,
            Yogyakarta, Indonesia. I interested in Web Development, i can do
            both Frontend and Backend but prefer the Backend one because i can't
            Design Content for Frontend.
          </p>
        </div>
        
        <h2 class="text-3xl font-bold text-left mt-52 mb-10 mx-2">Skills |</h2>
        <my-skill/>
      </div>
    <contact-me/>
    <footer-copy/>
  </div>
</template>
<script>
import NavTop from "@/components/NavTop.vue";
import MySkill from "@/components/Skill.vue";
import ContactMe from "@/components/Contact.vue";
import FooterCopy from "@/components/Footer.vue";
export default {
  name: "AboutView",
  components: {
    NavTop,
    ContactMe,
    MySkill,
    FooterCopy,
  },
};
</script>
<style>

.about {
  background-color: rgb(237, 244, 247);
}
</style>