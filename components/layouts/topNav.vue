<template lang="">
  <div>
    <div class="flex justify-end">
      <nuxt-link class="py-1 mx-2" v-for="link in navItems" :to="link.path">{{
        link.item
      }}</nuxt-link>
    </div>
  </div>
</template>

<script setup>
const navItems = ref([
  { item: "Dashboard", path: "/" },
  { item: "Finances", path: "/" },
  { item: "Github", path: "/" },
  { item: "Develop", path: "/" },
]);
</script>
