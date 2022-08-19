<template>
  <div class="main-div w-full">
    <div class="text-center w-full">
      <p class="text-2xl sm:text-lg">The Gods of Olympus have been waiting for your arrival!</p>
      <p class="text-2xl mb-10 sm:text-lg">Lock your Hero (NFT) and the Gods will award you tokens!</p>
    </div>
    <router-link to="farmer" class="flex-2 self-center block desktop:hidden mb-10 w-full">
      <button class="bg-blue-500 text-3xl px-5 py-3 border-2 border-solid border-white w-full">Stake NFTs</button>
    </router-link>
    <p class="text-2xl pt-5 border-t-4 desktop:text-4xl lg:text-3xl md:text-3xl sm:text-2xl text-center">Staking information</p>
    <div class="w-full flex py-5 gap-20">
      <div class="flex-1 w-full">
        <p class="w-full desktop:text-3xl lg:text-2xl md:text-2xl sm:text-xl mt-4">Reward per day: <div class="text-white desktop:text-3xl lg:text-2xl md:text-2xl sm:text-xl"><span class="desktop:text-4xl lg:text-3xl md:text-3xl sm:text-2xl text-red-500">2 - 10</span> <span class="desktop:text-5xl lg:text-4xl md:text-4xl sm:text-3xl text-yellow-500">HROM</span> depending on rarity of NFT hero</div></p>
        <p class="w-full desktop:text-3xl lg:text-2xl md:text-2xl sm:text-xl mt-4 border-solid border-t-2">Minimum staking period: <div class="text-white desktop:text-3xl lg:text-2xl md:text-2xl sm:text-xl"><span class="desktop:text-4xl lg:text-3xl md:text-3xl sm:text-2xl text-yellow-500">3 days</span></div></p>
        <p class="w-full desktop:text-3xl lg:text-2xl md:text-2xl sm:text-xl mt-4 border-solid border-t-2">Maximum staking period: <div class="text-white desktop:text-3xl lg:text-2xl md:text-2xl sm:text-xl"><span class="desktop:text-4xl lg:text-3xl md:text-3xl sm:text-2xl text-green-500">Unlimited</span></div></p>
        <p class="w-full desktop:text-3xl lg:text-2xl md:text-2xl sm:text-xl mt-4 border-solid border-t-2">Cooldown between stakings: <div class="text-white desktop:text-3xl lg:text-2xl md:text-2xl sm:text-xl"><span class="desktop:text-4xl lg:text-3xl md:text-3xl sm:text-2xl text-red-500">1 day</span></div></p>
        <p class="text-4xl mt-5 text-center w-full sm:text-2xl">Visit MARKETPLACE to spend your $HROM tokens</p>

      </div>
    <router-link to="farmer" class="flex-2 self-center hidden desktop:block">
      <button class="bg-blue-500 text-5xl px-10 py-5 border-2 border-solid border-white">Stake NFTs</button>
    </router-link>
    </div>
    
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { GEM_FARM_PROG_ID } from '@gemworks/gem-farm-ts';
export default defineComponent({
  setup() {
    return {
      GEM_FARM_PROG_ID,
    };
  },
});
</script>
<style scoped></style>
