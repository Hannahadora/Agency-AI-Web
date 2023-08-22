<template>
  <main class="index-hero md:pt-[150px] pt-[115px] -mt-[75px]">
    <div class="w-full">
      <div class="d-container mx-auto text-center">
        <article class="flex items-center justify-center mb-[32px]">
          <div class="px-[40px] py-[10px] rounded-[32px] bg-[#AB3ADD]">
            <p class="font-[600] lg:text-[24px] text-[20px] text-[#fff]">
              Welcome to the Future of Running an Agency Using AI
            </p>
          </div>
        </article>
        <h2
          class="font-[700] lg:text-[48px] text-[28px] text-[#333] lg:mx-[50px] md:mx-[24px]"
        >
          New 4-in-1 <span class="text-[#AB3ADD]">Agency App</span> Setup & Runs
          an Entire <span class="text-[#3B57F4]">Agency</span> In
          <span class="text-[#3B57F4]">ANY Niche</span> Using AI
        </h2>

        <p
          class="text-[#293272] font-[500] text-[24px] mt-[40px] lg:mx-[150px] md:mx-[70px] mx-[36px]"
        >
          App Setups the Agency, <b>Finds and Filters Jobs</b> that can be
          rendered using AI, Uses <b>Automated AI Service Agents</b> To Deliver
          Services Completely Hands-Free For YOU and Helps
          <b>Manage the agency as you scale</b>.
        </p>
      </div>
      <div
        class="w-[90%] mx-auto white-blue-grad lg:mb-[0] mb-[50px] mt-[40px] px-[10px] pb-[16px]"
      >
        <div class="pt-[31px] bg-[#fff] px-[24px]">
          <h4
            class="text-center text-[#4B4B4B] font-[900] lg:text-[24px] text-[20px]"
          >
            The Ultimate Agency Profit Machine Includes:
          </h4>
          <div
            class="grid lg:grid-cols-4 md:grid-cols-2 grid-cols-1 pt-[30px] pb-[10px]"
          >
            <div class="flex text-left px-[11px] pt-[10px] border-r">
              <SharedBlueMiniCard>
                <img class="" src="/icons/defisetup.svg" alt="Defi setup icon"
              /></SharedBlueMiniCard>
              <div class="ml-[10px]">
                <h6 class="mb-[8px] text-px] font-[800] text-[#3B57F4]">
                  DFY AI Agency Setup
                </h6>
                <p class="text-[14px] font-[400] text-[#7A7A7A]">
                  To help your subscribers quickly set up an Agency in any niche
                </p>
              </div>
            </div>
            <div class="flex text-left px-[11px] py-[10px] border-r">
              <SharedBlueMiniCard
                ><img
                  class=""
                  src="/icons/gig_finder.svg"
                  alt="Defi setup icon"
              /></SharedBlueMiniCard>
              <div class="ml-[10px]">
                <h6 class="mb-[8px] text-[16px] font-[800] text-[#3B57F4]">
                  AI Gig Finder
                </h6>
                <p class="text-[14px] font-[400] text-[#7A7A7A]">
                  To filter jobs/gigs that can be rendered using AI
                </p>
              </div>
            </div>
            <div class="flex text-left px-[11px] py-[10px] border-r">
              <SharedBlueMiniCard
                ><img class="" src="/icons/ser_agen.svg" alt="Defi setup icon"
              /></SharedBlueMiniCard>
              <div class="ml-[10px]">
                <h6 class="mb-[8px] text-[16px] font-[800] text-[#3B57F4]">
                  AI Service Agents 
                </h6>
                <p class="text-[14px] font-[400] text-[#7A7A7A]">
                  To deliver your chosen service using AI
                </p>
              </div>
            </div>
            <div class="flex text-left px-[11px] py-[10px]">
              <SharedBlueMiniCard>
                <img
                  class=""
                  src="/icons/agent_manager.svg"
                  alt="Defi setup icon"
              /></SharedBlueMiniCard>
              <div class="ml-[10px]">
                <h6 class="mb-[8px] text-[16px] font-[800] text-[#3B57F4]">
                  AI Agency Manager
                </h6>
                <p class="text-[14px] font-[400] text-[#7A7A7A]">
                  To Help Scale and manage your Agency
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="flex items-center justify-center">
        <img src="/images/hero-bg-img.png" alt="hero-img-1" />
      </div>
    </div>
  </main>
</template>

<script setup></script>

<style scoped>
.index-hero {
  background: url("/images/index_hero_bg.png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  max-height: 200vh;
  height: 100%;
}

.white-blue-grad {
  background: linear-gradient(
    to bottom,
    #ffffff 0%,
    #ffffff 60%,
    #3b57f415 70%,
    #3b57f415 20%,
    #e4e8ff 100%
  );
}
</style>
