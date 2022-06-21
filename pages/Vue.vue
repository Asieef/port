<template>
    <div class="font-display">
                <HomeBar/>
        <div>
            <img src="portfolio/vue-header.jpg" />
        </div>

        <div class="flex justify-center py-12">
            <h2 class="lg:text-3xl flex items-center font-display">Vue.JS - Vue Website
            </h2>
        </div>
        <div class="grid lg:grid-cols-2 gap-4 mx-auto container">
            <div class="col-span-1 lg:px-24 px-8">
                <p class="text-sm text-[#232323] font-medium leading-7">
                    This template has been made with Vue.JS Framework and CSS. The hot
                    reload (router) feature of Vue.JS makes the site very fast.

                <ul class=" list-disc px-4 py-2">
                    <li>Grid </li>
                    <li>Flex</li>
                    <li>Vue.JS</li>
                    <li>Vue Router</li>
                    <li>Hot Reload</li>

                </ul>
                </p>
            </div>

            <div class="col-span-1 text-[#232323] flex justify-center text-sm">
                <div>
                    <ul class="lg:px-20 px-8">
                        <li class="border-b border-[#fecd45] pb-4">
                            <h2 class="font-semibold">
                                Core Technologies :
                                <span class="font-light">HTML, CSS</span>
                            </h2>
                        </li>

                        <li class="border-b border-[#fecd45] py-4">
                            <h2 class="font-semibold">
                                Features :
                                <span class="font-light">Vue.JS, CSS, Grid, Flex</span>
                            </h2>
                        </li>

                        <li class="border-b border-[#fecd45] py-4">
                            <h2 class="font-semibold">
                                Frontend Tools :
                                <span class="font-light">Illustrator, Photoshop</span>
                            </h2>
                        </li>

                        <li class="border-b border-[#fecd45] py-4">
                            <h2 class="font-semibold">
                                Livedemo :
                                <a href="https://concept-asieef.vercel.app/" class="hover:text-gray-500" target="blank">
                                    <span class="font-light">https://concept-asieef.vercel.app/</span>
                                </a>
                            </h2>
                        </li>
                    </ul>
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