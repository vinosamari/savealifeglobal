<template>
  <div>
    <nuxt-img src="/volunteer.jpeg" class="image" />
    <section>
      <h2 class="header">Join our volunteer program today!</h2>
      <button>START HERE</button>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
div {
  @apply flex bg-green-700 items-center;
}
section {
  @apply flex flex-col gap-2 justify-center items-center text-center md:mx-auto p-3;
}
.header {
  @apply md:text-5xl font-customTwo tracking-widest text-xl md:mb-4 capitalize py-6;
}
.image {
  @apply h-32 md:h-64 object-contain;
}
button {
  @apply bg-green-900 text-black uppercase mx-auto px-4 mt-3 md:text-3xl py-2 text-xs tracking-wide cursor-pointer font-customThree font-bold;
}
</style>