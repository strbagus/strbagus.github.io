<template>
    <div id="hero" class="relative">
        <div class="header text-white absolute text-center">
            <div class="text-3xl">
                Hello, i'am 
            </div>
            <span class="name text-7xl text-yellow-500">Satrio Bagus</span>
            <div class="text-xl">Web Developer</div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HomeBanner',
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Oswald:wght@300&display=swap");

#hero {
    background-image: linear-gradient(45deg, #2a2b33, #16171C);
    background-size: cover; 
    height: 100vh;
}
#hero .header{
    top: 50%;
    width: 100%;
    /* IE 9 */
    -webkit-transform: translate(0, -50%);
    /* Safari */
    transform: translate(0, -50%);

}
#hero .header .name {
  font-family: "Oswald", sans-serif;
}
</style>
