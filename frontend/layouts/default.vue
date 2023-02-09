<template>
  <flowbite-main-nav
    :navigations="navigations"
  />

    <slot/>
  <flowbite-main-footer/>
</template>

<script setup>
const navigations = [
  {
    title: "Главная",
    href: "/",
  },
  {
    title: "Каталог",
    href: "/catalog",
  },
]
</script>

<style scoped>

</style>