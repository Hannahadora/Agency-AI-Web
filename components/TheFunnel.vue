<template>
  <div class="d-container pt-[150px] pb-[245px]">
    <div class="flex flex-col items-center justify-center mb-[113px] text-center">
      <div class="flex items-center justify-center text-center">
        <h3 class="funnel_section-title font-[700] lg:text-[64px] md:text-[50px] text-[40px]">The Funnel</h3>
        <img src="/icons/funnel_cash.svg" alt="illustrtaion" /></div>
      <p class="font-[700] md:text-[32px] text-[24px] mt-[24px]">
        Earn <span class="text-[#3B57F4]">50% Commissions</span> Across The
        Funnel
      </p>
    </div>
    <div class="grid md:grid-cols-2 grid-cols-1 space-x-[20px] items-start justify-center">
      <div class="flex flex-col items-center justify-center">
        <SharedFunnelCard bgColor="#3B57F4" price="47" title="Premium" curveFill="#7C90FF" />
      </div>
      <div class="flex flex-col items-center justify-center md:mt-[0px] mt-[40px]">
        <h4 class="mb-[40px] font-[700] md:text-[40px] text-[30px] text-center">
          OTO 1
        </h4>
        <SharedFunnelCard bgColor="#AB3ADD" price="97" title="Unlimited" curveFill="#DD8FFF" />
      </div>
      <div class="flex flex-col items-center justify-center md:mt-[0px] mt-[40px]">
        <h4 class="mb-[40px] font-[700] md:text-[40px] text-[30px] text-center">
          OTO 2
        </h4>
        <SharedFunnelCard :bg-color="'#0A9851'" price="67" title="Pro" curveFill="#20C773" />
      </div>
      <div class="flex flex-col items-center justify-center md:mt-[60px] mt-[40px]">
        <h4 class="mb-[40px] font-[700] md:text-[40px] text-[30px] text-center">
          OTO 3
        </h4>
        <SharedFunnelCard bgColor="#38088B" price="197" title="Enterprise" curveFill="#5D19D3" />
      </div>
      <div class="flex flex-col items-center justify-center md:mt-[0px] mt-[40px]">
        <h4 class="mb-[40px] font-[700] md:text-[40px] text-[30px] text-center">
          OTO 4
        </h4>
        <SharedFunnelCard bgColor="#2F2F2F" price="67" title="Content Burger" curveFill="#5E5E5E" />
      </div>
      <div class="flex flex-col items-center justify-center md:mt-[60px] mt-[40px]">
        <h4 class="mb-[40px] font-[700] md:text-[40px] text-[30px] text-center">
          OTO 5
        </h4>
        <SharedFunnelCard bgColor="#E49700" price="197" title="Agency Scale WhiteLabel" curveFill="#FFD164" />
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.funnel_section-title {
  background: linear-gradient(155deg, #3b57f4 0%, #ab3add 95.79%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  line-height: 137.687%; /* 88.12px */
}
</style>
