<template>
  <div>
    <article class="a-box md:px-[60px] px-[20px] md:py-[38px] py-[30px] mb-[27px]">
        <div class="w-full flex items-center justify-between">
          <img
            class="md:mr-[30px] mr-[10px]"
            src="/images/launch-icon.png"
            alt="launch-icon"
          />
          <div class="w-full flex md:flex-row flex-col items-center justify-between">
            <p>
              <span class="uppercase md:text-[24px] text-[18px] text-[#E8B5FF] font-[500]"
                >Launching On</span
              >
              <br /><br />
              <span class="text-[#fff] md:text-[36px] text-[24px] font-[700]"
                >24th August 2023</span
              >
            </p>
            <div class="md:px-[26px] px-[20px] md:py-[19px] py-[14px] rounded-[19px] bg-[#E8B5FF] md:mt-[0] mt-[20px]">
              <p class="font-[600] md:text-[30px] text-[24px] text-[#000]">@ 11AM ET/NY</p>
            </div>
          </div>
        </div>
      </article>

  </div>
</template>

<script setup>
</script>

<style scoped>
.a-box {
  border-radius: 24px;
  background: #8a00c7;
  box-shadow: 8px 8px 64px 0px rgba(171, 58, 221, 0.2);
  height: auto;
}
</style>