<template>
  <section>
    <div class="drop-shadow-md px-6 py-8 bg-white rounded-lg my-10">
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

        <div class="mt-8 lg:mt-0 lg:w-1/2">
          <div class="flex items-center justify-center lg:justify-end">
            <div class="max-w-lg">
              <img
                class="
                  object-cover object-center
                  w-full
                  h-64
                  rounded-md
                  shadow
                  hover:scale-105
                "
                src="../assets/profile-photo.jpg"
                alt="Profile Poto"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="drop-shadow-md px-6 py-8 bg-white rounded-lg">
      <h1 class="text-3xl font-bold">Skills</h1>
      <div class="items-center lg:flex">
        <div class="lg:w-1/2 px-5">
          <div class="flex flex-col items-center justify-center lg:justify-end">
            HTML & CSS
            <div class="w-full bg-gray-200 h-5 mb-6 text-right">
              <div class="bg-blue-600 h-5" style="width: 90%"></div>
            </div>
            PHP
            <div class="w-full bg-gray-200 h-5 mb-6 text-right">
              <div class="bg-blue-600 h-5" style="width: 75%"></div>
            </div>
            Javascript
            <div class="w-full bg-gray-200 h-5 mb-6 text-right">
              <div class="bg-blue-600 h-5" style="width: 60%"></div>
            </div>
            MYSQL
            <div class="w-full bg-gray-200 h-5 mb-6 text-right">
              <div class="bg-blue-600 h-5" style="width: 60%"></div>
            </div>
          </div>
        </div>
        <div class="lg:w-1/2 px-5">
          <div
            class="flex flex-col items-center justify-center lg:justify-start"
          >
            Tailwind CSS
            <div class="w-full bg-gray-200 h-5 mb-6 text-right">
              <div class="bg-blue-600 h-5" style="width: 55%"></div>
            </div>
            Laravel
            <div class="w-full bg-gray-200 h-5 mb-6 text-right">
              <div class="bg-blue-600 h-5" style="width: 40%"></div>
            </div>
            Vue
            <div class="w-full bg-gray-200 h-5 mb-6 text-right">
              <div class="bg-blue-600 h-5" style="width: 35%"></div>
            </div>
          </div>
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