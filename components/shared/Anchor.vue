
<script setup>
const props = defineProps(['href', 'text', 'isExternal'])
</script>

<template>
    <a v-if="isExternal" :href="href">{{ text }}</a>
    <NuxtLink v-else :to="href">{{ text }}</NuxtLink>
</template>

<style scoped>
a {
text-decoration: none;
background-image: linear-gradient(#1e4c7c, #1e4c7c);
background-size: 0% 0.1em;
background-position-y: 100%;
background-position-x: 0%;
background-repeat: no-repeat;
transition: background-size 0.2s ease-in-out;
}
a:hover,
a:focus,
a:active {
background-size: 100% 0.1em;
}
</style>