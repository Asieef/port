<template>
    <div class="font-display">
                <HomeBar/>
                <div class=" grid grid-flow-row justify-items-center">
        <div class="border-2 p-4">
            <img src="portfolio/remax-header.jpg" />
        </div>

        <div class="flex justify-center py-12">
            <h2 class="lg:text-3xl flex items-center font-display">Remax-ECommerce Site | Nuxt.JS
            </h2>
        </div>
        <div class="grid lg:grid-cols-2 mx-auto container gap-4">
            <div class="col-span-1 lg:px-24 px-8">
                <p class="text-sm text-[#232323] font-medium leading-7">
                   This site has been made using Nuxt.JS framwork. API has
                   been to used to fetch product data. The site is responsive
                   and the mobile version has a Off canvas menu. 

                <ul class=" list-disc px-4 py-2">
                    <li>Grid </li>
                    <li>Flex</li>
                    <li>Off canvas menu</li>
                    <li>Transition</li>
                    <li>Animation</li>
                    <li>Mobile Responsive</li>

                </ul>
                </p>
            </div>

            <div class="col-span-1 text-[#232323] flex justify-center text-sm">
                <div>
                    <ul class="lg:px-20 px-8">
                        <li class="border-b border-[#fecd45] pb-4">
                            <h2 class="font-semibold">
                                Core Technologies :
                                <span class="font-light">HTML, Tailwind, Javascript</span>
                            </h2>
                        </li>

                        <li class="border-b border-[#fecd45] py-4">
                            <h2 class="font-semibold">
                                Features :
                                <span class="font-light">Mobile Responsive,CSS,Transition, Menu</span>
                            </h2>
                        </li>

                        <li class="border-b border-[#fecd45] py-4">
                            <h2 class="font-semibold">
                                Front-end Tools :
                                <span class="font-light">Illustrator, Photoshop</span>
                            </h2>
                        </li>

                        <li class="border-b border-[#fecd45] py-4">
                            <h2 class="font-semibold">
                                Livedemo :
                                <a href="https://iremax.com.bd/" class="hover:text-gray-500" target="blank">
                                    <span class="font-light">https://iremax.com.bd/</span>
                                </a>
                            </h2>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        </div>
    </div>
</template>

<style>
.font-display {
    font-family: "Montserrat";
}
</style>