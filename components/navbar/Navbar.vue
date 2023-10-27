<template>
  <div class="h-full items-center flex gap-4 italic">
    <a href="/about">about</a>
    <a href="/contact">contact</a>
  </div>
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