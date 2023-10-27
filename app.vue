<template>
  <div class="grid grid-cols-7">
    <div class="hidden md:inline-flex p-3">
      <NuxtLink to="/">
        <img src="/img/concorde.png" alt="Concorde" />
      </NuxtLink>
    </div>
    <div class="col-span-6 pl-8">
      <Navbar />
    </div>
    <div class="md:col-span-1"></div>
    <div class="px-5 md:px-0 col-span-7 md:col-span-6">
      <NuxtPage />
    </div>
  </div>
  <div class="md:hidden p-12">
    <NuxtLink to="/">
      <img src="/img/concorde_mobile.png" alt="Concorde" />
    </NuxtLink>
  </div>
</template>
