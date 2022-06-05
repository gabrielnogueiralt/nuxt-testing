<template>
  <div class="bg-gray-100">
    <div class="container mx-auto flex items-center space-x-4 h-10 mb-10">
      <NuxtLink :to="{ name: 'about-company' }"> About </NuxtLink>
      <NuxtLink :to="{ name: 'services-list' }">Services</NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderItems',
}
</script>

<style></style>
