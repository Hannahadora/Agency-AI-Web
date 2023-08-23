<template>
  <section class="relative wrapper lg:py-[160px] sm:py-[110px] py-[40px]">
    <div class="d-container">
     <div class="flex sm:flex-row flex-col sm:items-end sm:space-x-12 sm:text-left text-center">
        <h1 class="lg:text-[60px] text-[36px] font-bold sm:pt-[100px] pt-[40px] inline">
        Start/Run Your <span class="bg-gradient-to-r from-[#AB3ADD] to-[#3B57F4] text-transparent bg-clip-text">AI <br> Agency</span> In Any Niche <br> In 3 Easy Steps!
        <img class="!inline sm:w-auto w-[40px]" src="/icons/startrun_star.svg" />
      </h1>
      <img class="sm:w-auto w-[140px] mx-auto sm:mt-0 mt-[20px]" src="/icons/start_vector.svg" alt="">
    </div>

     
     <div class="relative">
        <div class="sm:grid block grid-cols-2 relative z-50">
            <img class="w-full order-2" src="/icons/start_one.svg" alt="">
            <img class="w-full order-1 row-span-2 sm:mt-[200px]" src="/icons/start_two.svg" alt="">
            <img class="w-full order-3" src="/icons/start_three.svg" alt="">
        </div>
     <img class="absolute top-10 left-[50px] sm:block hidden" src="/icons/start_loop.svg" alt="">
     </div>
    </div>
  </section>
</template>
    
    <script setup lang="ts"></script>
    
    <style scoped>
.wrapper {
  background: url("/icons/startrun.svg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
</style>
    