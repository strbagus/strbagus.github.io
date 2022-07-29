<template>
  <div
    class="flex flex-col items-center justify-between px-6 py-8 bg-gradient-to-r from-sky-500 to-indigo-500"
  >
    <div class="flex flex-row text-white py-10">
      <div v-for="contact in contacts" :key="contact.name">
        <a :href="contact.href" target="_blank">
          <button
            type="button"
            data-mdb-ripple="true"
            data-mdb-ripple-color="light"
            :class="`
              lg:mx-5
              mx-1
              inline-block
              px-6
              py-2.5
              mb-2
              text-white
              font-medium
              text-xs
              leading-tight
              uppercase
              rounded
              shadow-md
              hover:shadow-lg
              focus:shadow-lg focus:outline-none focus:ring-0
              active:shadow-lg
              transition
              duration-150
              ease-in-out
              ${contact.style}
            `"
          >
            <img :src="contact.pic" :alt="contact.name" class="w-6 h-6">
          </button>
        </a>
      </div>
    </div>
    <a href="http://mailto:satrio.baguswbw@gmail.com" target="_blank" class="text-white text-center">
      satrio.baguswbw@gmail.com
    </a>
  </div>
</template>

<script>
export default {
  name: "ContactMe",
  data: () => ({
    contacts: [
      { name: "github", href: "https://github.com/strbagus", pic: "/github-white.svg", style: "hover:bg-gradient-to-r bg-gray-800 hover:from-gray-800 hover:to-gray-900" },
      { name: "gitlab", href: "https://gitlab.com/strbagus", pic: "/gitlab-white.svg", style: "hover:bg-gradient-to-r bg-orange-500 hover:from-orange-500 hover:to-orange-600" },
      { name: "instagram", href: "https://instagram.com/baguswptro", pic: "/instagram.svg", style: "hover:bg-gradient-to-r bg-gradient-to-r from-pink-500 to-indigo-500 hover:from-pink-500 hover:to-indigo-600" },
      { name: "telegram", href: "https://t.me/strbagus", pic: "/telegram.svg", style: "hover:bg-gradient-to-r bg-cyan-600 hover:from-cyan-600 hover:to-cyan-700" },
    ],
  }),
};
</script>