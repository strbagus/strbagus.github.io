<template>
  <div class="my-10">
    <h1 class="text-2xl text-red-500">Web Development</h1>
    <div class="container flex-wrap lg:flex">
      <div class="lg:w-1/3 p-3 flex">
        <IconHtml />
        <div class="flex flex-col my-3" style="width: 100%">
          <div class="flex justify-between">
            <span>HTML</span>
          </div>
          <div class="w-full bg-gray-200 rounded-full ml-1 h-5 text-right shadow-lg ">
            <div class="bg-gradient-to-r rounded-full from-yellow-500 to-orange-600 h-5" style="width: 90%"></div>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 p-3 flex">
        <IconCss />
        <div class="flex flex-col my-3" style="width: 100%">
          <div class="flex justify-between">
            <span>CSS</span>
          </div>
          <div class="w-full bg-gray-200 rounded-full ml-1 h-5 text-right shadow-lg ">
            <div class="bg-gradient-to-r rounded-full from-yellow-500 to-orange-600 h-5" style="width: 80%"></div>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 p-3 flex">
        <IconJavascript />
        <div class="flex flex-col my-3" style="width: 100%">
          <div class="flex justify-between">
            <span>Javascript</span>
          </div>
          <div class="w-full bg-gray-200 rounded-full ml-1 h-5 text-right shadow-lg ">
            <div class="bg-gradient-to-r rounded-full from-yellow-500 to-orange-600 h-5" style="width: 65%"></div>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 p-3 flex">
        <IconMysql />
        <div class="flex flex-col my-3" style="width: 100%">
          <div class="flex justify-between">
            <span>MySQL</span>
          </div>
          <div class="w-full bg-gray-200 rounded-full ml-1 h-5 text-right shadow-lg ">
            <div class="bg-gradient-to-r rounded-full from-yellow-500 to-orange-600 h-5" style="width: 70%"></div>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 p-3 flex">
        <IconPhp />
        <div class="flex flex-col my-3" style="width: 100%">
          <div class="flex justify-between">
            <span>PHP</span>
          </div>
          <div class="w-full bg-gray-200 rounded-full ml-1 h-5 text-right shadow-lg ">
            <div class="bg-gradient-to-r rounded-full from-yellow-500 to-orange-600 h-5" style="width: 75%"></div>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 p-3 flex">
        <IconTailwind />
        <div class="flex flex-col my-3" style="width: 100%">
          <div class="flex justify-between">
            <span>Tailwindcss</span>
          </div>
          <div class="w-full bg-gray-200 rounded-full ml-1 h-5 text-right shadow-lg ">
            <div class="bg-gradient-to-r rounded-full from-yellow-500 to-orange-600 h-5" style="width: 75%"></div>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 p-3 flex">
        <IconLaravel />
        <div class="flex flex-col my-3" style="width: 100%">
          <div class="flex justify-between">
            <span>Laravel</span>
          </div>
          <div class="w-full bg-gray-200 rounded-full ml-1 h-5 text-right shadow-lg ">
            <div class="bg-gradient-to-r rounded-full from-yellow-500 to-orange-600 h-5" style="width: 40%"></div>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 p-3 flex">
        <!-- <img src="@/assets/logo/vuejs.svg" alt="vuejs" class="mx-2 my-3" style="width: 48px"> -->
        <IconVue />
        <div class="flex flex-col my-3" style="width: 100%">
          <div class="flex justify-between">
            <span>Vue.js</span>
          </div>
          <div class="w-full bg-gray-200 rounded-full ml-1 h-5 text-right shadow-lg ">
            <div class="bg-gradient-to-r rounded-full from-yellow-500 to-orange-600 h-5" style="width: 45%"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import IconCss from '@/components/icons/IconCss.vue';
import IconVue from '@/components/icons/IconVue.vue';
import IconLaravel from '@/components/icons/IconLaravel.vue';
import IconPhp from '@/components/icons/IconPhp.vue';
import IconMysql from '@/components/icons/IconMysql.vue';
import IconHtml from '@/components/icons/IconHtml.vue';
import IconJavascript from '@/components/icons/IconJavascript.vue';
import IconTailwind from '@/components/icons/IconTailwind.vue';
export default {
  name: "MySkill",
  components: {
    IconCss,
    IconVue,
    IconLaravel,
    IconPhp,
    IconMysql,
    IconHtml,
    IconJavascript,
    IconTailwind,
  },
};
</script>