<script setup lang="ts">
import DiscordIcon from './icons/DiscordIcon.vue'
import InstagramIcon from './icons/InstagramIcon.vue'
import MenuIcon from './icons/MenuIcon.vue'
import TwitterIcon from './icons/TwitterIcon.vue'
import WalletIcon from './icons/WalletIcon.vue'
</script>

<template>
  <header class="header">
    <div>
      <img src="/logo.png" alt="logo" width="148" height="47" />
    </div>
    <nav class="hidden lg:block">
      <ul class="flex items-center font-bold gap-8">
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
      <twitter-icon class-name="hidden md:block" />
      <discord-icon />
      <instagram-icon />
      <wallet-icon />
    </div>
    <div class="lg:hidden">
      <menu-icon />
    </div>
  </header>
</template>

<style scoped>
.header {
  @apply flex items-center justify-between pt-6 px-4;
  max-width: 1200px;
  margin: 0 auto;
}
</style>
