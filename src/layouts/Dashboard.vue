<template>
  <div class="bg-gray-800 flex text-white max-h-screen h-screen">
    <div class="w-64">
      <span class="font-semibold p-6 block opacity-90">skateboard</span>
      
      <nav class="p-6">
        <h3 class="opacity-50 uppercase font-semibold tracking-wider mb-6 text-xs">Menu</h3>

        <div class="space-y-6">
          <menu-item :icon="HomeIcon">Discover </menu-item>
          <menu-item :icon="TrendingUpIcon">Trending</menu-item>
          <menu-item :icon="TrendingUpIcon">Trending</menu-item>
          <menu-item :icon="TrendingUpIcon">Trending</menu-item>
          <menu-item :icon="TrendingUpIcon">Trending</menu-item>
          <menu-item :icon="TrendingUpIcon">Trending</menu-item>
        </div>
      </nav>
    </div>

    <div class="p-5 flex-1">
      <header>
        <input-search />

        <dropdown>
          <avatar />

        </dropdown>

        <notifications /> -->
      </header>
    </div>
  </div>
</template>

<script lang="ts" setup>
import MenuItem from './navs/MenuItem.vue'
import HomeIcon from '../components/icons/HomeIcon.vue'
import TrendingUpIcon from '../components/icons/TrendingUpIcon.vue'
import InputSearch from '../components/inputs/InputSearch.vue'
</script>

<style>

</style>