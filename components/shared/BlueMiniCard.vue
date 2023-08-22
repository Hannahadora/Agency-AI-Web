<template>
  <main
    class="relative flex items-center justify-center min-w-[74px] min-h-[80px]"
  >
    <div
      class="absolute top-0 rounded-[3px] bg-[#E4E8FF] min-w-[55px] mx-auto min-h-[80px]"
    ></div>
    <div
      class="absolute top-0 rounded-[3px] bg-[#E4E8FF] min-w-[65px] mx-auto min-h-[77px]"
    ></div>
    <div
      class="absolute top-0 rounded-[10px] bg-[#E4E8FF] w-[72px] h-[74px] px-[4px] py-[4px]"
    >
      <div class="flex items-center justify-center mt-[4px]">
        <slot></slot>
      </div>
    </div>
  </main>
</template>

<script setup lang="ts"></script>

<style></style>
