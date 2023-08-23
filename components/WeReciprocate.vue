<template>
    <section class="relative wrapper lg:py-[100px] sm:py-[50px] py-[30px]">
        <div class="d-container">
            <h1
                class="lg:text-[60px] sm:text-[36px] text-[28px] font-bold sm:pt-[50px] pt-[20px] text-center bg-gradient-to-b from-[#3B57F4] to-[#AB3ADD] text-transparent bg-clip-text">
                We Reciprocate
            </h1>
            <h2 class="text-[#333] sm:text-[30px] text-[18px] text-center pt-[20px]">When We Go Out We Go HARD <br> And Your
                Participation On This Launch Won’t Go Unnoticed!</h2>

            <div class="grid lg:grid-cols-3 sm:grid-cols-2 grid-cols-1 sm:gap-20 gap-10 sm:py-[100px] py-[50px]">
                <div v-for="(item, index) in cardData" :key="index"
                    class="sm:w-[315px] w-full bg-[#fff] sm:px-[45px] px-[20px] sm:py-[35px] py-[20px] rounded-[20px]">
                    <img :src="item.icon" alt="">
                    <p class="sm:text-[20px] text-[16px] sm:mt-[30px] mt-[18px] sm:h-[160px] h-auto">{{ item.desc }}</p>
                    <h1 class="text-[26px] font-bold pt-[30px] pb-[50px text-[#3B57F4]">{{ item.amount }}</h1>
                </div>
            </div>

            <!-- Part 2 -->
            <div class="grid lg:grid-cols-3 sm:grid-cols-2 grid-cols-1">
                <div class="flex flex-col items-center justify-between">
                    <div class="h-[100px] w-[100px] bg-[#3B57F4] rounded-full flex items-center justify-center"><img
                            src="/icons/gold_medal.svg" alt=""></div>
                    <div class="w-[10px] bg-black h-auto">.</div>
                    <div><img src="/icons/trophy.svg" alt=""></div>
                </div>

                <div class="flex">
                    <div class="w-[10px] bg-black h-[100%] rounded-[20px] -mr-[55px]">.</div>
                    <div class="flex flex-col items-center justify-between">
                        <div v-for="(item, index) in ladderDataOne" :key="index" class="border border-red-500 flex items-center space-x-5 my-[20px]">
                            <img class="w-[100px] h-[100px] bg-black rounded-full p-2" :src="item.icon" alt="">
                            <div class="border border-green-500">
                                <p class="">{{ item.title}}</p>
                                <h1 class="sm:text-[28px] text-[18px] text-[#333] font-bold">{{ item.amount }}</h1>
                            </div>
                            
                        </div>
                    </div>
                </div>

                <div class="flex">
                    <div class="w-[10px] bg-black h-[100%] rounded-[20px] -mr-[55px]">.</div>
                    <div class="flex flex-col items-center justify-between">
                        <div v-for="(item, index) in ladderDataTwo" :key="index" class="border border-red-500 flex items-center space-x-5 my-[20px]">
                            <img class="w-[100px] h-[100px] bg-black rounded-full p-2" :src="item.icon" alt="">
                            <div class="border border-green-500">
                                <p class="">{{ item.title}}</p>
                                <h1 class="sm:text-[28px] text-[18px] text-[#333] font-bold">{{ item.amount }}</h1>
                            </div>
                            
                        </div>
                    </div>
                </div>
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
                    amount: '$6,500+',
                    desc: "I did a combined 4-figure promo for the VideoRemix Team with over 87 sales on #SmartVideo Revolution.",
                    icon: "/icons/reci_videoremix.svg",
                },
                {
                    amount: '$10,200',
                    desc: "I did a combined 5-figure promo for the Adacomply Team with over 248 sales on #SmartVideo Evolution.",
                    icon: "/icons/reci_acada.svg",
                },
                {
                    amount: '$5,5000',
                    desc: "I delivered over $5,000 in sales for Chris Jenkins and Steve Rosembaun for EZDeals.",
                    icon: "/icons/e_deals.svg",
                },
                {
                    amount: '$9,000+',
                    desc: "Delivered over $9,000 in sales for the 2021 Launch of Markepresso by Karthik and Saurabh. #3 Position for the entire Launch.",
                    icon: "/icons/market_expresso.svg",
                },
                {
                    amount: '$5,000+',
                    desc: "Over $5,000 in sales for Mo Latif ClickDesign earlier this Year",
                    icon: "/icons/click_designs.svg",
                },
                {
                    amount: '$6,000+',
                    desc: "One of my best Launches, Delivered a stunning 110 Sales in 24 Hours and over $6,000 in sales for Abhi and Neil.",
                    icon: "/icons/vidtik.svg",
                },
            ],

            ladderDataOne: [
                {
                    title: '7DDL',
                    amount: '$3,000+',
                    icon: "/icons/landlord.svg",
                },
                {
                    title: 'MarketingBlocks',
                    amount: '$2,500+',
                    icon: "/icons/marketing_blocks.svg",
                },
                {
                    title: '7DDL',
                    amount: '$3,000+',
                    icon: "/icons/landlord.svg",
                },
            ],
            ladderDataTwo: [
                {
                    title: '7DDL',
                    amount: '$3,000+',
                    icon: "/icons/landlord.svg",
                },
                {
                    title: 'MarketingBlocks',
                    amount: '$2,500+',
                    icon: "/icons/marketing_blocks.svg",
                },
                {
                    title: '7DDL',
                    amount: '$3,000+',
                    icon: "/icons/landlord.svg",
                },
            ]
        };
    }
};
</script>


<style scoped>
.wrapper {
    background: url("/icons/bg_reciprocate.svg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}

.launch {
    background: url("/icons/launch_circle.svg");
    background-repeat: no-repeat;
    background-position: center;
    padding: 13px;
}

.card {
    box-shadow: 0px 61px 80px 0px rgba(59, 87, 244, 0.10);
}
</style>