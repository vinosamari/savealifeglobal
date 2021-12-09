<template>
  <section>
    <h1 class="header">
      Due to your contributions we now have a more robust trauma response unit.
      <span class="thankYou">Thank you!</span>
    </h1>
    <nuxt-img src="/paramedic.jpeg" class="image" />
    <div class="twoCardGrid">
      <div class="card">
        <h2 class="subheader">
          Over 500 volunteering elderly Cargivers and Nurses
        </h2>
        <nuxt-img src="/oldpeople2.jpeg" class="cardImage" />
      </div>
      <div class="card">
        <h2 class="subheader">
          dedicated alzheimer's programme and special care unit
        </h2>
        <nuxt-img src="/oldpeoplehands.jpeg" class="cardImage" />
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
section {
  @apply p-4 bg-customTwo pt-8;
}
.header {
  @apply font-customThree capitalize tracking-wider text-center px-4 md:text-4xl;
}
.subheader {
  @apply font-customThree capitalize px-8 text-center md:text-3xl;
}
.image {
  @apply object-cover h-1/2 w-3/4 mx-auto mt-4 mb-8 rounded-md shadow-2xl;
}
.twoCardGrid {
  @apply md:grid grid-cols-2;
}
.card {
  @apply mx-3 rounded-md shadow-2xl py-6 my-2;
}
.cardImage {
  @apply object-cover h-64 w-3/4 mx-auto mt-4 mb-8 rounded-md;
}
.thankYou {
  @apply font-bold;
}
</style>