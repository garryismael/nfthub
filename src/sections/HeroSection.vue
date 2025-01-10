<template>
  <section class="grid grid-cols-1 lg:grid-cols-2 pt-[78px]">
    <div class="px-4 text-center">
      <h1>High Quality NFT Collection</h1>
      <p class="px-1 pg-1">
        A 890 piece custom Nfthub's collection is joining the NFT space on Opensea.
      </p>
      <button class="flex items-center gap-3 mx-auto rounded-full btn-gradient mt-9">
        <span>View in OPENSEA</span>
        <font-awesome-icon :icon="faArrowUp" size="lg" class="rotate-45" />
      </button>
      <div class="flex items-center justify-center gap-5 mt-11">
        <div class="flex justify-center">
          <img
            src="/user-1.png"
            alt="user 1"
            width="600"
            height="600"
            class="w-12 h-12 border-4 border-white rounded-full"
          />
          <img
            src="/user-2.png"
            alt="user 1"
            width="600"
            height="600"
            class="w-12 h-12 -ml-5 border-4 border-white rounded-full"
          />
          <img
            src="/user-3.png"
            alt="user 1"
            width="600"
            height="600"
            class="w-12 h-12 -ml-5 border-4 border-white rounded-full"
          />
        </div>
        <div class="flex flex-col items-start">
          <h2 class="leading-none">47k+</h2>
          <p class="pg-2">Community members</p>
        </div>
      </div>
    </div>
    <div class="px-5 pt-7">
      <img src="/hero.png" alt="Hero Image" width="651" height="639" />
    </div>
  </section>
</template>
<script setup>
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { faArrowUp } from '@fortawesome/free-solid-svg-icons'
</script>
<style scoped>
h1 {
  @apply text-[40px] leading-10 lg:leading-[72px] lg:text-7xl;
  color: #0f051d;
  font-weight: 700;
}

h2 {
  @apply leading-none font-bold;
  color: #0f051d;
  font-size: 32px;
}

.pg-1 {
  @apply text-[19px] lg:text-[22px] leading-[30px] lg:leading-9 mt-6;
  color: #7b7583;
  font-weight: 400;
}

.pg-2 {
  color: #7b7583;
  font-size: 12px;
  font-weight: 400;
}
</style>
