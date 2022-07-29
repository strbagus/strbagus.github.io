<template>  
    <h2 class="text-red-500 text-2xl font-medium">What I Use</h2>
    <div v-for="cat in categories" >
        <h3 class="bg-yellow-400 text-xl text-white my-2 rounded"> {{cat}} </h3>
        <div class="flex justify-center">
            <div v-for="stack in stacks" v-bind:key="stack.name">
                <div v-if="cat == stack.cat" class="mx-2">
                    <img :src="`src/assets/icons/${stack.pic}`" :alt="stack.name" class="w-16 h-16" label="sss">
                    {{ stack.name }}
                </div>
            </div>
        </div>
    </div>
</template>
<script type="ts">
export default {
    name: "TechStacks",
    data: () => ({
        categories: ["Basic", "Frontend", "Backend", "Package Manager", "Tools"],
        stacks: [
            { cat: "Basic", name: "Html", pic: "html5.svg" },
            { cat: "Basic", name: "Css", pic: "css3.svg" },
            { cat: "Basic", name: "Javascript", pic: "javascript.svg" },
            { cat: "Basic", name: "PHP", pic: "php.svg" },
            { cat: "Frontend", name: "Tailwind", pic: "tailwind-css.svg" },
            { cat: "Frontend", name: "Vue", pic: "vuejs.svg" },
            { cat: "Frontend", name: "Ionic", pic: "ionic.svg" },
            { cat: "Backend", name: "Laravel", pic: "laravel.svg" },
            { cat: "Backend", name: "MYSQL", pic: "mysql.svg" },
            { cat: "Package Manager", name: "NPM", pic: "npm.svg" },
            { cat: "Tools", name: "Git", pic: "git.svg" },
            { cat: "Tools", name: "Gitlab", pic: "gitlab.svg" },
            { cat: "Tools", name: "Github", pic: "github.svg" },
        ]
    }),
}
</script>
<style scoped>
    div{
        color: black;
    }
</style>