<template>
  <main class="relative contest_section py-[100px]">
    <div class="relative d-container py-[36px]">
      <img
        class="absolute top-[-35px] right-[270px]"
        src="/icons/dollar-coin-lg.svg"
        alt="illustration"
      />
      <img
        class="absolute top-[85px] left-[350px]"
        src="/icons/dollar-coin-md.svg"
        alt="illustration"
      />
      <h3 class="contest_section-title font-[700] text-[64px] text-center">
        The Contest
      </h3>

      <div class="flex items-center justify-center mt-[20px] mb-[-40px]">
        <img class="" src="/icons/dollar-coin-sm.svg" alt="illustration" />
      </div>
      <section class="purple_bg_sect px-[150px] pt-[100px] pb-[150px] rounded-[48px]">
        <div class="flex flex-col items-center justify-center">
          <img class="" src="/images/cahp-t.png" alt="cash prize text" />
          <img src="/icons/curly-arrow.svg" alt="illustration" />
          <div class="purple_sect2 px-[56px] py--[16px] mt-[20px] text-center">
            <p class="leading-[58px] text-[30px]">
              <span class="font-[500] text-[#FFD164]"
                >72 Hrs Opening Contest: </span
              ><span class="font-[700] text-[#fff]"> 24th - 27th July</span>
            </p>
          </div>

          <div
            class="w-full mt-[80px] grid grid-cols-3 items-end justify-between"
          >
            <div class="flex flex-col items-center justify-center">
              <img src="/icons/second_place.svg" alt="second_place" />
              <div class="mt-[24px] text-center">
                <p class="text-[24px] font-[500] text-[#fff]">2nd Place</p>
                <p class="text-[32px] font-[700] text-[#fff]">$750</p>
              </div>
            </div>
            <div class="flex flex-col items-center justify-center">
              <img src="/icons/first_place.svg" alt="first_place" />
              <div class="mt-[24px] text-center">
                <p class="text-[32px] font-[500] text-[#fff]">1st Place</p>
                <p class="text-[38px] font-[700] text-[#fff]">$1,500</p>
              </div>
            </div>
            <div class="flex flex-col items-center justify-center">
              <img src="/icons/third_place.svg" alt="third_place" />
              <div class="mt-[24px] text-center">
                <p class="text-[24px] font-[500] text-[#fff]">3rd Place</p>
                <p class="text-[32px] font-[700] text-[#fff]">$500</p>
              </div>
            </div>
          </div>
          <div class="mt-[60px] w-full grid grid-cols-2 items-end justify-center">
            <div class="flex flex-col items-center justify-center">
              <img src="/icons/third_place.svg" alt="third_place" />
              <div class="mt-[24px] text-center">
                <p class="text-[24px] font-[500] text-[#fff]">4th Place</p>
                <p class="text-[32px] font-[700] text-[#fff]">$100</p>
              </div>
            </div>
            <div class="flex flex-col items-center justify-center">
              <img src="/icons/third_place.svg" alt="third_place" />
              <div class="mt-[24px] text-center">
                <p class="text-[24px] font-[500] text-[#fff]">5th Place</p>
                <p class="text-[32px] font-[700] text-[#fff]">$50</p>
              </div>
            </div>
          </div>

          <div
            class="mt-[80px] px-[36px] py-[26px] rounded-[8px] bg-[#8B20B9] flex items-center"
          >
            <img
              src="/icons/yellow_warning.svg"
              alt="illus"
              class="mr-[24px]"
            />
            <div>
              <p class="text-[20px] font-[700] text-[#FFD164]">
                TEAMS OF 2 ALLOWED
              </p>
              <p class="text-[16px] text-[#fff] font-[400]">
                Must Be Announced Before The Launch Goes Live
              </p>
            </div>
          </div>
        </div>
      </section>
    </div>
      <div class="absolute bottom-[-80px] left-[50%]">
        <img src="/icons/curly-spring-purplebg.svg" alt="curly-spring" />
      </div>
  </main>
</template>

<script setup lang="ts"></script>

<style scoped>
.contest_section {
  width: 100%;
  background: url("/icons/contest_section-bg.svg");
  background-repeat: no-repeat;
}

.contest_section-title {
  background: linear-gradient(155deg, #3b57f4 0%, #ab3add 95.79%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  line-height: 137.687%; /* 88.12px */
}

.purple_bg_sect {
  width: 100%;
  height: 100%;
  background: url("/icons/contest-section-purplebg.svg");
  background-repeat: no-repeat;
  background-position: center;
  border-radius: 48px;
}
.purple_sect2 {
  border-radius: 100px;
  background: #8a00c7;
  box-shadow: 0px 61px 80px 0px rgba(101, 27, 134, 0.35);
}
</style>
