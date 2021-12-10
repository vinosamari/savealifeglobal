<template>
  <section>
    <div class="subtitled">
      <h2 class="header">200 Pandemic test kits dispatched weekly</h2>
      <button>REQUEST YOUR KIT TODAY</button>
    </div>
    <nuxt-img src="/pandemictestkit.jpeg" class="image" />
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
section {
  @apply bg-green-800 flex md:flex-row flex-col text-center;
}
.subtitled {
  @apply flex flex-col gap-3 mx-auto my-auto;
}
.image {
  @apply h-44 md:h-64 rounded-md object-cover;
}
.header {
  @apply font-customTwo tracking-widest text-xl text-black md:text-4xl py-5 px-3 mx-auto;
}
button {
  @apply bg-green-700 font-bold font-customTwo tracking-wide mx-auto mb-5 rounded-md px-3 py-1 transform hover:scale-110 duration-500 transition-all hover:bg-green-900 md:text-2xl;
}
</style>