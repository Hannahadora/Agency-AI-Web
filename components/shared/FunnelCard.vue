<template>
  <div
    :class="`bg-[${bgColor}] h-full max-h-[509px] max-w-[392px] w-[100%] relative px-[10px] md:py-[57px] py-[30px] rounded-[24px] border border-[#D7D7D7] overflow-hidden`"
  >
    <div class="flex flex-col items-center justify-center">
        <SvgFunnelDiamond :diamondFill="bgColor" />
        <h5 class="md:text-[34px] text-[24px] font-[700] md:mt-[32px] mt-[24px] text-[#fff]">AgencyAI</h5>
        <div class="bg-[#fff] text-center py-[22px] px-[39px] md:mt-[57px] mt-[30px] max-w-[300px]">
            <p :class="`text-[${bgColor}] md:text-[24px] text-[20px] font-[600] uppercase`">{{title}}</p>
        </div>
        <p class="md:mt-[38px] mt-[30px] font-[600] text-[60px] text-[#fff] text-center">${{ price }}</p>
    </div>

    <SvgFunnelCurve :curveFill="curveFill" class="absolute bottom-[-10px] left-0" />
  </div>
</template>

<script setup lang="ts">
defineProps({
    curveFill: {
        type: String,
        default: '#fff'
    },
    bgColor: {
        type: String,
        default: ''
    },
    title: {
        type: String,
        default: 'Title'
    },
    price: {
        type: String,
        default: 'Price'
    }
})
</script>

<style></style>
