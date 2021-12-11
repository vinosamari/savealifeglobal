<template>
  <footer>
    <h1 class="date">{{ this.date }}</h1>
    <div class="otherLinks">
      <li>Anonymous Donations</li>
      <li>Newsletter</li>
      <li>Gallery</li>
      <li>Alzeimer's Programme</li>
    </div>
    <div class="copy">© save a life global initiative</div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      date: new Date().toDateString(),
    };
  },
};
</script>

<style scoped>
footer {
  @apply font-customTwo md:text-3xl grid grid-cols-2  items-center bg-customThree p-3;
}
.otherLinks {
  @apply row-span-2 list-none mx-auto font-bold underline md:flex;
}
.copy {
  @apply capitalize;
}
li {
  @apply md:mx-5 md:text-2xl my-3 text-xs tracking-widest md:tracking-normal text-right cursor-pointer;
}
</style>