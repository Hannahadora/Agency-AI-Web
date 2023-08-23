<template>
    <section class="relative wrapper lg:py-[160px] sm:py-[110px] py-[40px]">
        <div class="d-container">
            <h1 class="lg:text-[60px] sm:text-[36px] text-[28px] font-bold sm:pt-[100px] pt-[40px] text-center">
                TOP <span class="text-[#AB3ADD]">5</span> <span
                    class="italic text-[#AB3ADD] reasons sm:bg-auto bg-cover font-normal lg:text-[55px] sm:text-[36px] text-[24]">Reasons</span> <br> Your Customers Will
                Love <br>
                <span class="text-[#3B57F4]">AgencyAI</span>
            </h1>

            <div class="max-w-[850px] mx-auto lg:py-[120px] sm:py-[80px] py-[30px]">
                <div v-for="(item, index) in cardData" :key="index"
                    class="bg-white card sm:grid grid-cols-7 block items-center sm:space-x-10 sm:p-[24px] p-[12px] mb-[37px]">
                    <span
                        class="sm:mb-0 mb-[20px] sm:!h-[100px] !h-[50px] sm:!w-[100px] !w-[50px] rounded-full bg-[#E7EAFF] text-[#3B57F4] sm:text-[40px] text-[20px] font-bold flex items-center justify-center">
                        {{ item.number }}
                    </span>
                    <div class="col-span-6">
                        <h1 class="sm:text-[24px] text-[18px] font-bold pb-[12px]">{{ item.title }}</h1>
                        <p class="sm:text-[20px] text-[15px]">{{ item.description }}</p>
                    </div>
                </div>
            </div>


            <div class="">
                <img class="mx-auto cursor-pointer" src="/icons/top_btnn.svg" alt="">

                <div class="max-w-[640px] mx-auto text-center sm:text-[24px] text-[18px] py-[30px]">
                    <span class="text-[#3B57F4] text-center font-bold">PLUS</span>:we're including hand-picked
                    exclusive bonuses in the front-end offer as well as each OTO, well suited to your subscribers to make
                    them drool…
                </div>


                <button class="sm:mt-[60px] mt-[30px] mx-auto flex items-center justify-center space-x-4 bg-[#3B57F4] text-white shadow-[0px 16px 80px 0px rgba(59, 87, 244, 0.30)] rounded-full px-6 py-4">
                    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 41 41" fill="none">
                        <path
                            d="M20.4999 9.02051C14.0566 9.02051 8.83325 14.2439 8.83325 20.6872C8.83325 27.1305 14.0566 32.3538 20.4999 32.3538C26.9433 32.3538 32.1666 27.1305 32.1666 20.6872"
                            stroke="white" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" />
                        <path d="M22.1665 19.0212L33.8332 7.35449" stroke="white" stroke-width="3" stroke-linecap="round"
                            stroke-linejoin="round" />
                        <path d="M25.5 5.6875H35.5V15.6875" stroke="white" stroke-width="3" stroke-linecap="round"
                            stroke-linejoin="round" />
                    </svg>

                    <span>Get Your Affiliate Link Now</span>
                </button>
            </div>

        </div>
        <img class="absolute lg:block hidden  bottom-[500px] left-10" src="/icons/top_goldstar.svg" alt="">
        <img class="absolute lg:block hidden  bottom-[140px] right-80" src="/icons/top_mugu_robot.svg" alt="">

    </section>
</template>
      
<script>
export default {
    data() {
        return {
            cardData: [
                {
                    number: 1,
                    title: "It'll make them SERIOUS MONEY by leveraging AI from a single dashboard!",
                    description: "(We have proof!) Beta AgencyAI Customers used it to massively boost their profits WITHOUT using multiple tools & platforms."
                },
                {
                    number: 2,
                    title: "It's SUPER FAST!",
                    description: "Your customers will be able to render the hottest in-demand services super quick & enjoy 100% Uptime."
                },
                {
                    number: 3,
                    title: "It costs next to nothing.",
                    description: "The amount of money AgencyAI is going to save your customers in recurring payments (that they would have had to pay otherwise to freelancers & agencies) added to the early bird discounted one-time price makes this a steal."
                },
                {
                    number: 4,
                    title: "It has a UNIVERSAL APPEAL!",
                    description: "It appeals to absolutely everybody: AgencyAI can be used to increase sales and profits by EVERYBODY in EVERY NICHE."
                },
                {
                    number: 5,
                    title: "It's an AWESOME DEAL.",
                    description: "The quality of AgencyAI and the genuineness of this offer is going to blow your customers away and make their decision to click that buy button easily."
                },
            ]
        };
    }
};
</script>


<style scoped>
.wrapper {
    background: url("/icons/bg_topfive.svg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}

.reasons {
    background: url("/icons/reason_ccircle.svg");
    background-repeat: no-repeat;
    background-position: center;
    /* background-size: cover; */
    padding: 13px;
}

.card {
    box-shadow: 0px 61px 80px 0px rgba(59, 87, 244, 0.10);
}</style>