<template>
  <div
    class="nav top-0 sticky bg-gray-800 text-yellow-500 p-3 drop-shadow-lg z-10"
  >
    <div class="container mx-auto flex justify-center">
      <a href="#/" class="flex hover:text-yellow-600 :">
        <img
          src="../assets/logo.svg"
          alt="Logo Strbagus"
          style="height: 30px"
        />
        <div class="text-xl ml-4">strbagus</div>
      </a>
      <!--       
      <div class="flex">
        <a href="#/" class="mx-5 text-xl hover:text-yellow-600">Home</a>
        <a href="#/about" class="mx-5 text-xl hover:text-yellow-600">About</a>
        <a href="#/portfolio" class="mx-5 text-xl hover:text-yellow-600"
          >Portfolio</a
        >
      </div> -->
    </div>
  </div>
</template>

<script>
export default {
  name: "NavTop",
};
</script>