<template>
  <nav>
    <div class="logo">save a life global</div>
    <div class="links">
      <li>Donations</li>
      <li>Partners</li>
      <li>Projects</li>
      <li>Contact</li>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
nav {
  @apply flex items-center justify-center bg-customFive flex-col md:flex-row md:justify-between py-2;
}
.logo {
  @apply font-customTwo md:text-3xl font-black p-2 tracking-wider capitalize px-8 border-b-4 border-green-900 mb-4 md:border-0 mx-auto md:mx-0 md:my-auto;
}
.links {
  @apply text-gray-200 list-none grid grid-cols-2 md:flex md:justify-around text-center;
}
.links li {
  @apply bg-customFour rounded mx-auto px-3 p-1 my-2 md:mx-4 font-customThree md:text-lg cursor-pointer;
}
</style>