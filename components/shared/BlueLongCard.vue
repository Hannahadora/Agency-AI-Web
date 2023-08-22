<template>
  <main class="blc relative">
    <div class="z-[5] bg-[#F5F7FF] py-[24px] pl-[32px] pr-[58px] flex items-center justify-center rounded-[10px]">
      <SharedBlueMiniCard  class="mr-[24px]">
        <img :src="icon" alt="icons" />
      </SharedBlueMiniCard>
      <slot></slot>
    </div>
    <div class="z-[2] bg-[#3B57F41F] max-w-[609px] mx-auto min-h-[48px] mt-[-40px] rounded-[10px]"></div>
    <div class="z-[2] bg-[#3B57F41F] max-w-[573px] mx-auto min-h-[58px] mt-[-50px] rounded-[10px]"></div>
  </main>
</template>

<script setup lang="ts">
defineProps({
  icon: {
    type: String,
    default: "",
  },
});
</script>

<style scoped>
.blc {
    max-width: 678px;
  /* background: url("/icons/blue-long-card.svg"); */
  background-repeat: no-repeat;
}
</style>
