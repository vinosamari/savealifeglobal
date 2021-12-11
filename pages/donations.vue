<template>
  <div>
    <section>
      <h1>Make a donation towards saving a life today</h1>
      <main class="intlTransfer">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 512 512"
          height="3rem"
          class="icon"
        >
          <path
            d="M256 416c114.9 0 208-93.1 208-208S370.9 0 256 0 48 93.1 48 208s93.1 208 208 208zM233.8 97.4V80.6c0-9.2 7.4-16.6 16.6-16.6h11.1c9.2 0 16.6 7.4 16.6 16.6v17c15.5.8 30.5 6.1 43 15.4 5.6 4.1 6.2 12.3 1.2 17.1L306 145.6c-3.8 3.7-9.5 3.8-14 1-5.4-3.4-11.4-5.1-17.8-5.1h-38.9c-9 0-16.3 8.2-16.3 18.3 0 8.2 5 15.5 12.1 17.6l62.3 18.7c25.7 7.7 43.7 32.4 43.7 60.1 0 34-26.4 61.5-59.1 62.4v16.8c0 9.2-7.4 16.6-16.6 16.6h-11.1c-9.2 0-16.6-7.4-16.6-16.6v-17c-15.5-.8-30.5-6.1-43-15.4-5.6-4.1-6.2-12.3-1.2-17.1l16.3-15.5c3.8-3.7 9.5-3.8 14-1 5.4 3.4 11.4 5.1 17.8 5.1h38.9c9 0 16.3-8.2 16.3-18.3 0-8.2-5-15.5-12.1-17.6l-62.3-18.7c-25.7-7.7-43.7-32.4-43.7-60.1.1-34 26.4-61.5 59.1-62.4zM480 352h-32.5c-19.6 26-44.6 47.7-73 64h63.8c5.3 0 9.6 3.6 9.6 8v16c0 4.4-4.3 8-9.6 8H73.6c-5.3 0-9.6-3.6-9.6-8v-16c0-4.4 4.3-8 9.6-8h63.8c-28.4-16.3-53.3-38-73-64H32c-17.7 0-32 14.3-32 32v96c0 17.7 14.3 32 32 32h448c17.7 0 32-14.3 32-32v-96c0-17.7-14.3-32-32-32z"
          />
        </svg>
        <h2 class="intlTransferHeader">International Wire Transfers</h2>
        <h3 class="acctNumber">Account Number: 92389435201</h3>
        <h4 class="routingNumber">Routing Number: 27483478</h4>
        <h4 class="swiftCode">Swift Code: 4X832A</h4>
      </main>
      <section class="inCityPickup">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 640 512"
          height="2.5rem"
        >
          <path
            d="M621.3 237.3l-58.5-58.5c-12-12-28.3-18.7-45.3-18.7H480V64c0-17.7-14.3-32-32-32H32C14.3 32 0 46.3 0 64v336c0 44.2 35.8 80 80 80 26.3 0 49.4-12.9 64-32.4 14.6 19.6 37.7 32.4 64 32.4 44.2 0 80-35.8 80-80 0-5.5-.6-10.8-1.6-16h163.2c-1.1 5.2-1.6 10.5-1.6 16 0 44.2 35.8 80 80 80s80-35.8 80-80c0-5.5-.6-10.8-1.6-16H624c8.8 0 16-7.2 16-16v-85.5c0-17-6.7-33.2-18.7-45.2zM80 432c-17.6 0-32-14.4-32-32s14.4-32 32-32 32 14.4 32 32-14.4 32-32 32zm128 0c-17.6 0-32-14.4-32-32s14.4-32 32-32 32 14.4 32 32-14.4 32-32 32zm272-224h37.5c4.3 0 8.3 1.7 11.3 4.7l43.3 43.3H480v-48zm48 224c-17.6 0-32-14.4-32-32s14.4-32 32-32 32 14.4 32 32-14.4 32-32 32z"
          />
        </svg>
        <h2 class="inCityHeader">In-City Pickups</h2>
        <p class="inCitySummary">
          Call your nearest
          <span class="saveALifeSpan">save a life global</span>Ⓡ pickup center
          for pickups of clothes,toys,books and stationeries.
        </p>
      </section>
    </section>
  </div>
</template>

<script>
export default {
  components: {},
};
</script>

<style scoped>
div {
  @apply bg-green-700 min-h-screen py-5 px-3;
}
.intlTransfer,
.inCityPickup {
  @apply border-4 border-black rounded-md mx-auto h-auto md:w-1/3 flex flex-col items-center justify-center font-customOne shadow-2xl mt-4 p-3;
}
.inCityPickup {
  @apply md:px-16 px-3 text-center;
}
.intlTransferHeader,
.inCityHeader {
  @apply md:text-2xl font-bold antialiased;
}
h1 {
  @apply font-customTwo md:text-3xl text-center capitalize;
}
.image {
  @apply w-3/4 h-3/4 rounded-md object-cover;
}
.inCitySummary {
  @apply text-lg text-center mt-2 tracking-wide;
}
.saveALifeSpan {
  @apply font-customTwo font-bold md:text-2xl;
}
.icon {
  @apply my-2;
}
</style>