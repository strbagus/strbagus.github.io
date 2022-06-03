<template>
  <section>
    <div class="py-8 my-10">
      <div class="items-center lg:flex">
        <div class="lg:w-1/2">
          <h2 class="text-3xl font-bold text-gray-800">Who I am</h2>

          <p class="mt-4 text-gray-500 text-justify">
            Hi I am bagus, Software Engineering student at SMKN 1 Bantul,
            Yogyakarta, Indonesia. I interested in Web Development, i can do
            both Frontend and Backend but prefer the Backend one because i can't
            Design Content for Frontend.
          </p>
          <a href="#/about">
            <button
              class="
                mt-3
                px-2
                py-1
                font-medium
                tracking-wide
                text-white
                capitalize
                transition-colors
                duration-200
                transform
                bg-blue-600
                rounded-md
                hover:bg-blue-500
                focus:outline-none
                focus:ring
                focus:ring-blue-300
                focus:ring-opacity-80
              "
            >
              More
            </button>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "AboutMe",
};
</script>