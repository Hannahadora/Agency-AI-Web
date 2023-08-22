<template>
  <section class="relative bg-[#fff] w-full py-[127px]">
    <div class="absolute top-[0px] flex items-center justify-center">
      <img class="" src="/icons/merge_spring.svg" alt="icon" />
    </div>
    <div class="d-container">
      <div class="threesbg lg:p-[24px] md:p-[12px] p-[8px]">
        <h3
          class="text-center lg:text-[60px] md:text-[40px] text-[30px] font-[700]"
        >
          Now What If YOU Could Start<br class="md:block hidden" />
          An <span class="text-[#3B57F4]">AI Agency </span>In Any Niche<br
            class="md:block hidden"
          />
          YOU Want In
          <span class="text-[#3B57F4]">SECONDS?</span>
        </h3>
      </div>
      <div class="mt-[80px]">
        <div class="flex flex-col items-center justify-center">
          <SharedBlueLongCard icon="/icons/solid-sun.svg" class="mb-[63px]">
            <p>
              What If YOU could
              <b>get EVERYTHING you need for your new agency</b> completely done
              for you… including Websites, Contact Forms, Cold Email Followup,
              Proposals, Banners, & much more?
            </p>
          </SharedBlueLongCard>
          <SharedBlueLongCard icon="/icons/robot-fill.svg">
            <p>
              What If YOU could <b>get AI Service Agents</b> that generate the
              most valuable results & output from AI?
            </p>
          </SharedBlueLongCard>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped>
.threesbg {
  background: url("/icons/three_step_bg.svg");
  background-repeat: no-repeat;
  background-position: center;
}
</style>
