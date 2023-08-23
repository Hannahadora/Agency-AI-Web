<template>
    <section class="relative wrapper lg:py-[160px] sm:py-[110px] py-[40px]">
        <div class="d-container">
            <h1 class="text-center lg:text-[60px] text-[36px] font-[700] pb-[50px] text-white">
                Here's What's Inside <br> AgencyAI
            </h1>

            <div class="bg-white rounded-[10px] sm:py-[90px] py-[40px] lg:px-[90px] sm:px-[45px] px-[20px]">
                <div class="text-center mx-auto">
                    <img class="mx-auto" src="/icons/inside_feature_one.svg" alt="">
                    <h1
                        class="lg:text-[48px] sm:text-[36px] text-[24px] bg-gradient-to-r from-[#AB3ADD] to-[#3B57F4] text-transparent bg-clip-text pt-[43px] font-[700]">
                        DFY AI Agency Setup</h1>
                    <h2 class="sm:text-[30px] text-[18px] pt-[10px]">With 1 Click AI Installation Wizard</h2>
                </div>

                <div
                    class="flex sm:flex-row flex-col items-start justify-center sm:space-x-10 sm:space-y-0 space-y-6 sm:my-[80px]  my-[30px]">
                    <div class="lg:max-w-[430px] sm:max-w-[300px] sm:max-w-[90%]">
                        <h1 class="lg:text-[30px] sm:text-[22px] text-[18px] font-[700] pb-[16px]">
                            SETUP A PROFESSIONAL PORTFOLIO WEBSITE + MARKETING RESOURCES TO SELL YOUR AI SERVICES WITH WITH
                            AI IN A FEW CLICKS
                        </h1>
                        <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                            A completely functional & customizable website with a home page, portfolio, & contact us page to
                            display your business & AI services.
                        </p>
                        <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                            Every business would like to see your professional portfolio from the past. We got you covered.
                            Instantly display your AI services on your own personalized website, which is included in
                            AgencyAI.
                        </p>
                        <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                            You also get professionally developed marketing resources like Commercial Videos, Proposals, and
                            a lot more.
                        </p>
                        <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3 font-[700]">
                            [Market Price: $997]
                        </p>
                    </div>
                    <div class="sm:max-w-[500px] max-w-[100%] w-full relative sm:ml-[300px]">
                        <img class="w-full" src="/icons/inside_img_one.svg" alt="illustration" />
                    </div>
                </div>


                <div class="sm:py-0 py-[20px]">
                    <h1 class="lg:text-[30px] sm:text-[26px] text-[18px] font-[700] text-center"> AI Agency Installation
                        Wizard.</h1>
                    <div class="max-w-[620px] mx-auto pt-[25px] pb-[40px]">
                        <p class="text-center sm:text-[16px] text-[14px]">We have the Entire AI Agency Setup as Easy and
                            Seamless as Possible. This Way, Users can get a
                            Complete Agency Website in 50 Niches with a Few Clicks,
                            with Content and Custom Branding. <br> <br>
                            No Manual Installation adn We host the Website and the abilty
                            to setup custom domains.
                        </p>
                    </div>
                    <img class="w-full mx-auto" src="/icons/inside_img_two.svg" alt="illustration" />
                </div>

                 <!-- feature 2 -->
                <div class="sm:pt-[150px] pt-[40px]">
                    <div class="text-center mx-auto">
                        <img class="mx-auto" src="/icons/inside_feature_two.svg" alt="">
                        <h1
                            class="lg:text-[48px] sm:text-[36px] text-[24px] bg-gradient-to-r from-[#AB3ADD] to-[#3B57F4] text-transparent bg-clip-text pt-[43px] font-[700]">
                            40+ AI Service Agents</h1>
                        <h2 class="sm:text-[30px] text-[18px] pt-[10px]">With 4000+ dfy Prompts Triggers</h2>
                    </div>

                    <div
                        class="flex sm:flex-row-reverse flex-col-reverse items-start justify-center sm:space-x-10 sm:space-y-0 space-y-6 sm:my-[80px]  my-[30px]">
                        <div class="lg:max-w-[430px] sm:max-w-[300px] sm:max-w-[90%] sm:ml-[30px]">
                            <h1 class="lg:text-[30px] sm:text-[22px] text-[18px] font-[700] pb-[16px]">
                                LET AI SERVICE AGENTS AUTO DELIVER THE SERVICES IN MINUTES
                            </h1>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                These intelligent assistants, powered by cutting-edge AI technology, are designed to provide
                                targeted services tailored to your needs.
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                Our AI Service Agents understand your requirements and deliver precise assistance.
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                Simply select an agent, choose from customized prompts, and watch them generate expert-level
                                content.
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                Boost your productivity & unlock new possibilities with AI Service Agents, revolutionizing
                                the way you harness AI's power.
                            </p>
                        </div>
                        <div class="sm:max-w-[500px] max-w-[100%] w-full relative">
                            <img class="w-full" src="/icons/inside_img_three.svg" alt="illustration" />
                        </div>
                    </div>
                </div>

                <!-- break -->
                <div class="flex flex-wrap gap-y-10 sm:overflow-x-auto overflow-x-hidden pt-[40px] pb-[60px]">
                    <div v-for="(item, index) in cardItems" :key="index"
                        :class="['card', 'mx-auto', '-ml-[30px]', 'bg-white', 'h-[73px] w-[73px] rounded-[50%]', { 'expanded-card': item.expanded }]">
                        <img class="sm:h-[73px] h-[50px] sm:w-[73px] h-[50px] rounded-full border-2 cursor-pointer"
                            :src="item.icon" alt="" @click="toggleCardExpansion(index)" />
                        <h4 class="title font-medium overflow-ellipsis">{{ item.title }}</h4>
                    </div>
                </div>


                <!-- break -->
                <div
                    class="flex sm:flex-row flex-col items-start justify-center sm:space-x-10 sm:space-y-0 space-y-6 sm:my-[80px]  my-[30px]">
                    <div class="lg:max-w-[430px] sm:max-w-[300px] sm:max-w-[90%]">
                        <h1 class="lg:text-[30px] sm:text-[22px] text-[18px] font-[700] pb-[16px]">
                            Loaded With 4000+ Dfy Prompts Triggers
                        </h1>
                        <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                            AgencyAI Wont only provide AI Service Agents that users can chat with to Deliver the Service.
                        </p>
                        <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                            We have also loaded each Agent with DFY Prompts.
                        </p>
                        <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                            Select an AI Service Agent, and choose from a list of prompts tailored to your needs.
                        </p>
                        <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                            No more research or guesswork—get instant, top-notch results.
                        </p>
                    </div>
                    <div class="sm:max-w-[500px] max-w-[100%] w-full relative sm:ml-[300px]">
                        <img class="w-full" src="/icons/inside_img_four.svg" alt="illustration" />
                    </div>
                </div>

                <!-- feature 3 -->
                <div class="sm:pt-[150px] pt-[40px]">
                    <div class="text-center mx-auto">
                        <img class="mx-auto" src="/icons/inside_feature_three.svg" alt="">
                        <h1
                            class="lg:text-[48px] sm:text-[36px] text-[24px] bg-gradient-to-r from-[#AB3ADD] to-[#3B57F4] text-transparent bg-clip-text pt-[43px] font-[700]">
                            AI Gig Finder</h1>
                    </div>

                    <div
                        class="flex sm:flex-row-reverse flex-col-reverse items-start justify-center sm:space-x-10 sm:space-y-0 space-y-6 sm:my-[80px]  my-[30px]">
                        <div class="lg:max-w-[430px] sm:max-w-[300px] sm:max-w-[90%]">
                            <h1 class="lg:text-[30px] sm:text-[22px] text-[18px] font-[700] pb-[16px]">
                                BUILT-IN GIG FINDER FILTER SERVICES THAT CAN BE RENDERED USING AI
                            </h1>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                AI-Powered GIG Finder searches the web & filters jobs for you that can be easily rendered
                                using AgencyAI.
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                All you have to do is enter a keyword and let the AI find the best-paying services
                                instantly.
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                Save valuable time & resources that would otherwise be spent searching through countless job
                                postings to find the right match for your skills & expertise.
                            </p>
                        </div>
                        <div class="sm:max-w-[500px] max-w-[100%] w-full relative sm:ml-[300px]">
                            <img class="w-full" src="/icons/inside_img_five.svg" alt="illustration" />
                        </div>
                    </div>
                </div>

                <div
                    class="flex sm:flex-row sm:space-y-0 space-y-10 flex-col item-center justify-between sm:pb-[200px] pb-[80px]">
                    <div class="text-center sm:w-[250px] w-full">
                        <img class="mx-auto" src="/icons/inside_funnel.svg" alt="">
                        <h1 class="font-[700] sm:text-[20px] text-[16px] pt-[20px] pb-[10px]">Filter Gigs from Accros the Web
                        </h1>
                        <p class="sm:text-[16px] text-[14px]">With the Job Finder, Users can find Jobs on Demand.</p>
                    </div>
                    <div class="text-center sm:w-[250px] w-full">
                        <img class="mx-auto" src="/icons/inside_suitcase.svg" alt="">
                        <h1 class="font-[700] text-[20px] pt-[20px] pb-[10px]">Jobs On Demand</h1>
                        <p class="sm:text-[16px] text-[14px]">With the Job Finder, Users can find Jobs on Demand.</p>
                    </div>
                    <div class="text-center sm:w-[250px] w-full">
                        <img class="mx-auto" src="/icons/inside_briefcase.svg" alt="">
                        <h1 class="font-[700] text-[20px] pt-[20px] pb-[10px]">Predictable Earnings</h1>
                        <p class="sm:text-[16px] text-[14px]">The AI Job Finder offers users predictable revenue.</p>
                    </div>

                </div>


                <!-- break -->
                <div class="sm:pt-[150px] pt-[40px]">
                    <div class="text-center mx-auto">
                        <img class="mx-auto" src="/icons/inside_feature_three.svg" alt="">
                        <h1
                            class="lg:text-[48px] sm:text-[36px] text-[24px] bg-gradient-to-r from-[#AB3ADD] to-[#3B57F4] text-transparent bg-clip-text pt-[43px] font-[700]">
                            Email Follow-Up Engine</h1>
                        <h2 class="sm:text-[30px] text-[18px] pt-[10px]">(With Done-For-You Cold Email Swipes)</h2>
                    </div>

                    <div
                        class="flex sm:flex-row flex-col items-start justify-center sm:space-x-10 sm:space-y-0 space-y-6 sm:my-[80px]  my-[30px]">
                        <div class="lg:max-w-[430px] sm:max-w-[300px] sm:max-w-[90%]">
                            <h1 class="lg:text-[30px] sm:text-[22px] text-[18px] font-[700] pb-[16px]">
                                GENERATE LEADS, NURTURE EXISTING CUSTOMERS, & INCREASE SALES
                            </h1>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                Email marketing is a critical component of any successful business strategy.
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                However, crafting effective email campaigns that drive engagement & conversions can be a
                                challenging task, particularly for those who lack experience in this area.
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                Fortunately, AgencyAI has a built-in Email Follow-Up Engine that simplifies this process by
                                automating the creation & delivery of personalized email campaigns.
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                These emails have been carefully crafted by industry experts & tested for effectiveness,
                                ensuring that you get the highest levels of engagement & conversions.
                            </p>
                        </div>
                        <div class="sm:max-w-[500px] max-w-[100%] w-full relative sm:ml-[300px]">
                            <img class="w-full" src="/icons/inside_img_six.svg" alt="illustration" />
                        </div>
                    </div>
                </div>


                <!-- break 7 -->
                <div class="sm:pt-[150px] pt-[40px]">
                    <div class="text-center mx-auto">
                        <img class="mx-auto" src="/icons/inside_feature_three.svg" alt="">
                        <h1
                            class="lg:text-[48px] sm:text-[36px] text-[24px] bg-gradient-to-r from-[#AB3ADD] to-[#3B57F4] text-transparent bg-clip-text pt-[43px] font-[700]">
                            Client & Workspaces</h1>
                    </div>

                    <div
                        class="flex sm:flex-row-reverse flex-col-reverse items-start justify-center sm:space-x-10 sm:space-y-0 space-y-6 sm:my-[80px]  my-[30px]">
                        <div class="lg:max-w-[430px] sm:max-w-[300px] sm:max-w-[90%]">
                            <h1 class="lg:text-[30px] sm:text-[22px] text-[18px] font-[700] pb-[16px]">
                                MULTI-USER ACCESS FOR CLIENTS AND TEAM MEMBERS
                            </h1>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                Our dashboard has been designed for multiple user accounts, which means your TEAM & CLIENTS
                                can access it too.
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                Running your profitable business might require a pair of extra hands to manage small tasks
                                for you.
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                But with only one account, and literally your whole database on it, you might feel a bit
                                dicey handing over access to anyone other than yourself right?
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                Well, we have a solution for you.
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                Invite your team members to selectively manage certain client accounts. They can create and
                                grow client profiles for you, and you can monitor their work while still having master
                                control over your entire dashboard.
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                You can ALSO invite clients to monitor the progress of their projects.
                            </p>
                        </div>
                        <div class="sm:max-w-[500px] max-w-[100%] w-full relative sm:ml-[300px]">
                            <img class="w-full" src="/icons/inside_img_seven.svg" alt="illustration" />
                        </div>
                    </div>
                </div>




                <!-- break -->
                <div class="sm:pt-[150px] pt-[40px]">
                    <div class="text-center mx-auto">
                        <img class="mx-auto" src="/icons/inside_feature_three.svg" alt="">
                        <h1
                            class="lg:text-[48px] sm:text-[36px] text-[24px] bg-gradient-to-r from-[#AB3ADD] to-[#3B57F4] text-transparent bg-clip-text pt-[43px] font-[700]">
                            AI Agency Manager</h1>
                    </div>

                    <div
                        class="flex sm:flex-row flex-col items-start justify-center sm:space-x-10 sm:space-y-0 space-y-6 sm:my-[80px]  my-[30px]">
                        <div class="lg:max-w-[430px] sm:max-w-[300px] sm:max-w-[90%]">
                            <h1 class="lg:text-[30px] sm:text-[22px] text-[18px] font-[700] pb-[16px]">
                                MANAGE SERVICE DELIVERY TO CLIENTS & STREAMLINE OPERATIONS AS YOU SCALE
                            </h1>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                The AI Agency Manager works by utilizing advanced algorithms & machine learning technology
                                to identify the most efficient & cost-effective ways of delivering services to clients. </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                By analyzing factors such as client needs, project complexity, and resource availability…
                            </p>
                            <p class="lg:text-[20px] sm:text-[16px] text-[14px] pb-3">
                                … the AI Agency Manager can automatically assign tasks to team members, set deadlines, &
                                track progress, ensuring that projects are delivered on time
                            </p>

                        </div>
                        <div class="sm:max-w-[500px] max-w-[100%] w-full relative sm:ml-[300px]">
                            <img class="w-full" src="/icons/inside_img_eight.svg" alt="illustration" />
                        </div>
                    </div>
                </div>


                <div class="grid lg:grid-cols-3 sm:grid-cols-2 grid-cols-1 gap-8 sm:pb-[150px] pb-[60px]">
                    <div class="text-center sm:w-[250px] w-full">
                        <svg class="mx-auto" xmlns="http://www.w3.org/2000/svg" width="101" height="101" viewBox="0 0 101 101" fill="none">
                            <rect x="0.756836" y="0.788574" width="100" height="100" fill="#FAF0FF" />
                        </svg>
                        <h1 class="font-[700] sm:text-[20px] text-[16px] pt-[20px] pb-[10px]">AI Agency Consultant</h1>
                        <p class="sm:text-[16px] text-[14px]">Who knows about AI tools & platforms… and can help you set up an AI Agency.</p>
                    </div>

                    <div class="text-center sm:w-[250px] w-full">
                        <svg class="mx-auto" xmlns="http://www.w3.org/2000/svg" width="101" height="101" viewBox="0 0 101 101" fill="none">
                            <rect x="0.756836" y="0.788574" width="100" height="100" fill="#FAF0FF" />
                        </svg>
                        <h1 class="font-[700] sm:text-[20px] text-[16px] pt-[20px] pb-[10px]">AI Job Finder</h1>
                        <p class="sm:text-[16px] text-[14px]">Who scans & filters jobs/gigs for you that can be rendered using AI.</p>
                    </div>
                  
                    <div class="text-center sm:w-[250px] w-full">
                        <svg class="mx-auto" xmlns="http://www.w3.org/2000/svg" width="101" height="101" viewBox="0 0 101 101" fill="none">
                            <rect x="0.756836" y="0.788574" width="100" height="100" fill="#FAF0FF" />
                        </svg>
                        <h1 class="font-[700] sm:text-[20px] text-[16px] pt-[20px] pb-[10px]">AI Tools</h1>
                        <p class="sm:text-[16px] text-[14px]">That can generate high-quality content quickly & efficiently.</p>
                    </div>
                    <div class="text-center sm:w-[250px] w-full">
                        <svg class="mx-auto" xmlns="http://www.w3.org/2000/svg" width="101" height="101" viewBox="0 0 101 101" fill="none">
                            <rect x="0.756836" y="0.788574" width="100" height="100" fill="#FAF0FF" />
                        </svg>
                        <h1 class="font-[700] sm:text-[20px] text-[16px] pt-[20px] pb-[10px]">AI Agency Consultant</h1>
                        <p class="sm:text-[16px] text-[14px]">Who knows about AI tools & platforms… and can help you set up an AI Agency.</p>
                    </div>

                    <div class="text-center sm:w-[250px] w-full">
                        <svg class="mx-auto" xmlns="http://www.w3.org/2000/svg" width="101" height="101" viewBox="0 0 101 101" fill="none">
                            <rect x="0.756836" y="0.788574" width="100" height="100" fill="#FAF0FF" />
                        </svg>
                        <h1 class="font-[700] sm:text-[20px] text-[16px] pt-[20px] pb-[10px]">AI Job Finder</h1>
                        <p class="sm:text-[16px] text-[14px]">Who scans & filters jobs/gigs for you that can be rendered using AI.</p>
                    </div>
                  
                    <div class="text-center sm:w-[250px] w-full">
                        <svg class="mx-auto" xmlns="http://www.w3.org/2000/svg" width="101" height="101" viewBox="0 0 101 101" fill="none">
                            <rect x="0.756836" y="0.788574" width="100" height="100" fill="#FAF0FF" />
                        </svg>
                        <h1 class="font-[700] sm:text-[20px] text-[16px] pt-[20px] pb-[10px]">AI Tools</h1>
                        <p class="sm:text-[16px] text-[14px]">That can generate high-quality content quickly & efficiently.</p>
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
            cardItems: [
            { title: 'CopyWriter', icon: '/images/dummy_avatars/Avatar.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-1.png', expanded: false },
                { title: 'Web Developer', icon: '/images/dummy_avatars/Avatar-2.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-3.png', expanded: false },
                { title: 'Sales Representative', icon: '/images/dummy_avatars/Avatar-4.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-5.png', expanded: false },
                { title: 'Customer Assistant', icon: '/images/dummy_avatars/Avatar-6.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-7.png', expanded: false },
                { title: 'Therapist', icon: '/images/dummy_avatars/Avatar-8.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-9.png', expanded: false },
                { title: 'Graphic Designer', icon: '/images/dummy_avatars/Avatar-10.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-11.png', expanded: false },
                { title: 'Animator', icon: '/images/dummy_avatars/Avatar-12.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-13.png', expanded: false },
                { title: 'Product designer', icon: '/images/dummy_avatars/Avatar-14.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-15.png', expanded: false },
                { title: 'Customer Support', icon: '/images/dummy_avatars/Avatar-16.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-17.png', expanded: false },
                { title: 'Voice Artistr', icon: '/images/dummy_avatars/Avatar-18.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-19.png', expanded: false },
                { title: 'Affiliate Marketer', icon: '/images/dummy_avatars/Avatar-20.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-21.png', expanded: false },
                { title: 'Sales Representative', icon: '/images/dummy_avatars/Avatar-22.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-23.png', expanded: false },
                { title: 'Teacher', icon: '/images/dummy_avatars/Avatar-24.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-25.png', expanded: false },
                { title: 'Product Manager', icon: '/images/dummy_avatars/Avatar-26.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-27.png', expanded: false },
                { title: 'Editor', icon: '/images/dummy_avatars/Avatar-28.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-29.png', expanded: false },
                { title: 'Proofreader', icon: '/images/dummy_avatars/Avatar-30.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-31.png', expanded: false },
                { title: '', icon: '/images/dummy_avatars/Avatar-32.png', expanded: false },
                { title: 'Lots More', icon: '/icons/inside_lotsmore.svg', expanded: false },
            ]
        };
    },
    methods: {
        toggleCardExpansion(index) {
            this.cardItems.forEach((item, i) => {
                item.expanded = i === index;
            });
        }
    }
};
</script>
      
<style scoped>
.wrapper {
    background: url("/icons/bg_inside.svg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}

.title {
    max-width: 89px;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}

.expanded-card {
    margin-left: 30px;
    margin-right: 30px;
    transition: margin-left 0.3s ease-in-out;

}</style>
      