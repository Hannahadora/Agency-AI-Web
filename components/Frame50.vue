<template>
  <div class="d-container w-full bg-[#fff]">
    <div class="pt-[75px] pb-[158px] w-full">
      <SharedLaunchingInfo />
      <article class="a-box md:px-[55px] px-[20px] py-[38px] mb-[27px]">
        <div
          class="w-full flex md:flex-row flex-col items-center justify-center"
        >
          <div class="text-center md:mr-[55px]">
            <p class="font-[600] text-[#FFC236] text-[33px]">High Converting</p>
            <p class="text-[69px] text-[#fff] font-[800]">$445</p>
            <p class="font-[600] text-[#FFC236] text-[30px]">Funnel Potential</p>
          </div>
          <div
            class="md:my-0 md:my-[50px] my-[30px] bg-[#FF6FED] md:p-[14px] p-[10px] w-[50px] h-[50px] rounded-[100%] text-[#8D00C9] md:text-[28px] text-[20px] font-[500] flex items-center justify-center"
          >
            &
          </div>
          <img
            class="lg:ml-[55px]"
            src="/images/cahp-t.png"
            alt="cash prize text"
          />
        </div>
      </article>

      <SharedTicketForm />
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.a-box {
  border-radius: 24px;
  background: url('/icons/purple_bg-striped.svg');
  box-shadow: 8px 8px 64px 0px rgba(171, 58, 221, 0.2);
  height: auto;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
</style>
