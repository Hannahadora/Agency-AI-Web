<template>
    <section class="relative wrapper lg:py-[100px] sm:py-[50px] py-[30px]">
        <div class="d-container">
            <h1 class="lg:text-[60px] sm:text-[36px] text-[28px] font-bold sm:pt-[50px] pt-[20px] text-center bg-gradient-to-b from-[#3B57F4] to-[#000000] text-transparent bg-clip-text">
              Our Products Converts
            </h1>

            <div class="flex lg:flex-row flex-col sm:space-y-0 space-y-10 item-center justify-between sm:py-[100px] py-[50px]">
                <div v-for="(item, index) in cardData" :key="index" class="bg-gradient-to-r from-[#333333] to-[#5D5D5E] sm:px-[45px] px-[30px] py-[35px] rounded-[20px]">
                   <div class="cursor-pointer mx-auto text-[24px] text-center bg-[#AB3ADD] text-white py-4 px-6">Launch Revenue</div>
                   <h1 class="text-[54px] text-white font-bold pt-[30px] pb-[50px] text-center">{{ item.amount }}</h1>
                   <img class="mx-auto" :src="item.icon" alt="">
                </div>
            </div>

            <div class="max-w-[900px] text-center mx-auto sm:text-[24px] text-[18px] text-[#333333]">
                This is No 'Fluke', Together with My Partners, I have gone “all out” in terms of quality and production every single time in the past. No expense has been spared whatsoever. Rock solid products + Kick ass marketing funnels == $$
            </div>

            <div class="bg-white rounded-[16px] border border-[#E4A7FF] sm:p-[30px] p-[16px] sm:text-[32px] text-[24px] font-bold text-center mt-[48px] mb-[20px] max-w-[800px] mx-auto">
                History Repeats Itself …<span class="text-[#3B57F4;] launch  sm:bg-auto bg-cover">& August 31st</span> <br> Will Not Be An Exception
            </div>
         

        </div>

    </section>
</template>
      
<script>
export default {
    data() {
        return {
            cardData: [
                {
                    amount: '$700,000',
                    icon: "/icons/mobomatic.svg",
                },
                {
                    amount: '$100,000',
                    icon: "/icons/pandora.svg",
                },
                {
                    amount: '$210,000',
                    icon: "/icons/content_burger.svg",
                }
            ]
        };
    }
};
</script>


<style scoped>
.wrapper {
    background: url("/icons/bg_lobo.svg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}
.launch {
    background: url("/icons/launch_circle.svg");
    background-repeat: no-repeat;
    background-position: center;
    /* background-size: cover; */
    padding: 13px;
}
.card {
    box-shadow: 0px 61px 80px 0px rgba(59, 87, 244, 0.10);
}</style>