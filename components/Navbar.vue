<template>
  <nav>
    <nuxt-link class="logo" to="/">save a life global</nuxt-link>
    <div class="links">
      <nuxt-link to="/donations" class="link">Donations</nuxt-link>
      <li class="link">Partners</li>
      <li class="link">Projects</li>
      <li class="link">Contact</li>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
nav {
  @apply flex items-center justify-center bg-customThree flex-col md:flex-row md:justify-between py-2;
}
.logo {
  @apply font-customTwo md:text-3xl font-black p-2 tracking-wider capitalize px-8 border-b-4 border-green-900 mb-4 md:border-0 mx-auto md:mx-0 md:my-auto cursor-pointer;
}
.links {
  @apply text-gray-200 list-none grid grid-cols-2 md:flex md:justify-around text-center;
}
.link {
  @apply bg-customFour rounded mx-auto px-3 p-1 my-2 md:mx-4 font-customThree md:text-lg cursor-pointer transform hover:scale-110 transition-all duration-500 hover:bg-green-900;
}
</style>