<template>
  <header class="header">
    <div>
      <img src="/logo.png" alt="logo" width="148" height="47" />
    </div>
    <nav class="hidden lg:block">
      <ul class="flex items-center gap-8 font-bold">
        <li>
          <a href="#">Home</a>
        </li>
        <li>
          <a href="#">Collection</a>
        </li>
        <li>
          <a href="#">Choose</a>
        </li>
        <li>
          <a href="#">About</a>
        </li>
        <li>
          <a href="#">Roadmap</a>
        </li>
        <li>
          <a href="#">Blog</a>
        </li>
      </ul>
    </nav>
    <div class="flex items-center gap-5">
      <font-awesome-icon :icon="faTwitter" class="hidden md:block" size="lg" />
      <font-awesome-icon :icon="faDiscord" size="lg" />
      <font-awesome-icon :icon="faInstagram" size="lg" />
      <font-awesome-icon :icon="faWallet" size="lg" />
    </div>
    <div class="lg:hidden">
      <menu-icon />
    </div>
  </header>
</template>

<script setup>
import { faDiscord, faInstagram, faTwitter } from '@fortawesome/free-brands-svg-icons'
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { faWallet } from '@fortawesome/free-solid-svg-icons'
import MenuIcon from './icons/MenuIcon.vue'
</script>

<style scoped>
.header {
  @apply flex items-center justify-between pt-6 px-4;
  max-width: 1200px;
  margin: 0 auto;
}
</style>
