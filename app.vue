<template>
  <div class="grid grid-cols-7">
    <div class="p-3">
      <NuxtLink to="/">
        <img src="/img/concorde.png" alt="Concorde" />
      </NuxtLink>
    </div>
    <div class="col-span-6 pl-8">
      <Navbar />
    </div>
    <div class="col-span-1"></div>
    <div class="col-span-6">
      <NuxtPage />
    </div>
  </div>
</template>
