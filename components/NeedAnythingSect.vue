<template>
  <main class="ate-wrapper py-[80px]">
    <div class="d-container">
      <div class="lg:mx-[60px] mx-[10px]">
        <SharedLaunchingInfo />
        <SharedTicketForm />
      </div>
      <div
        class="md:pt-[240px] pt-[150px] flex flex-col items-center justify-center"
      >
        <div class="mt-[60px] mb-[43px] text-center">
          <h4
            class="nae-title font-[700] lg:text-[72px] md:text-[56px] text-[45px]"
          >
            Need Anything Else?
          </h4>
          <p
            class="mx-auto lg:w-[50%] w-[80%] mt-[26px] font-[500] md:text-[24px] text-[20px]"
          >
            If you need anything at all that can help you promote AgencyAI to
            your list… feel free to get in touch.
          </p>
        </div>
        <div>
          <img src="/icons/curly-spring.svg" alt="" />
        </div>
        <div class="flex md:flex-row flex-col items-center justify-center">
          <img src="/icons/godswillO.svg" alt="Godswill photo" />
          <div class="g-info-box px-[50px] py-[30px] md:mt-[0] mt-[20px]">
            <p class="text-[#333] font-[700] text-[24px]">Goodwill Okoyomon</p>
            <div class="mt-[20px] mx-[20px] flex items-center justify-between">
              <div class="flex items-center cursor-pointer">
                <img
                  class="mr-[8px]"
                  src="/icons/email_icon.svg"
                  alt="email"
                />Email
              </div>
              <div class="flex items-center cursor-pointer">
                <img
                  class="mr-[8px]"
                  src="/icons/skype_icon.svg"
                  alt="skype"
                />Skype
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script setup></script>

<style scoped>
.nae-title {
  background: linear-gradient(155deg, #3b57f4 0%, #ab3add 95.79%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  line-height: 137.687%; /* 88.12px */
}
.ate-wrapper {
  background: url("/icons/design_pattern_one.svg");
  background-repeat: no-repeat;
  /* background-position: center; */
  width: 100%;
  margin: 0;
}
.g-info-box {
  border-radius: 10px;
  background: linear-gradient(226deg, #fff 0%, rgba(255, 255, 255, 0) 100%);
}
</style>
