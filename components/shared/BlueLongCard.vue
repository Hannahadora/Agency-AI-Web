<template>
  <main class="blc relative">

    <div class="flex items-center">
        <div class="px-[24px] py-[25px] rounded-[50%] w-[60px] h-[60px] bg-[#E9ECFF] flex flex-col gap-[10px] items-center justify-center mr-[32px]">
            <p class="text-center text-[#3B57F4] text-[40px] font-[700]">?</p>
        </div>

       <div class="flex flex-col items-center justify-center">
            <div class="bg-[#F5F7FF] py-[24px] pl-[32px] pr-[58px] flex items-center justify-center rounded-[10px]">
                <div class="bg-[#E9ECFF] shadow rounded-[10px] flex items-center justify-center mr-[24px] px-[20px] py-[22px]">
                    <img :src="icon" alt="icons" />
                </div>
                <slot></slot>
            </div>
        </div>
    </div>
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
  background-repeat: no-repeat;
}
</style>
