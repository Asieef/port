<template>
    <div class="font-display">
                <HomeBar/>
                <div class=" grid grid-flow-row justify-items-center">
        <div class="border-2 p-4">
            <img src="portfolio/valuetop-header.jpg" />
        </div>

        <div class="flex justify-center py-12">
            <h2 class="lg:text-3xl flex items-center font-display">VALUETOP.NET API Based Website Design</h2>
        </div>
        <div class="grid lg:grid-cols-2 mx-auto container gap-4">
            <div class="col-span-1 lg:px-24 px-8">
                <p class="text-sm text-[#232323] font-medium leading-7">
                    This website is based on API, where the products are being fetched from
                    a JSON database. The site is designed with Tailwind CSS Framework.
                    Axios has been used to fetch the data, the site is fast and efficient
                    for users. Some technical specs of the project includes :

                <ul class=" list-disc px-4 py-2">
                    <li>Component Based</li>
                    <li>Nuxt SEO</li>
                    <li>Hot Reload</li>
                    <li>Mobile Responsive</li>
                    <li>Transition Animation</li>
                    <li>Conditional Rendering</li>
                    <li>Data Binding</li>
                    <li>List Output</li>
                    <li>Dynamic Class</li>
                    <li>Custom Events</li>

                </ul>
                </p>
            </div>

            <div class="col-span-1 text-[#232323] flex lg:justify-center text-sm">
                <div>
                    <ul class="lg:px-20 px-8">
                        <li class="border-b border-[#fecd45] pb-4">
                            <h2 class="font-semibold">
                                Core Technologies :
                                <span class="font-light">Vue.JS, Nuxt.JS, Tailwind CSS</span>
                            </h2>
                        </li>

                        <li class="border-b border-[#fecd45] py-4">
                            <h2 class="font-semibold">
                                Features :
                                <span class="font-light">Search, Loading Bar, Responsive</span>
                            </h2>
                        </li>

                        <li class="border-b border-[#fecd45] py-4">
                            <h2 class="font-semibold">
                                Front-end Tools:
                                <span class="font-light">Tailwind CSS, Illustrator, Photoshop</span>
                            </h2>
                        </li>

                        <li class="border-b border-[#fecd45] py-4">
                            <h2 class="font-semibold">
                                Livedemo :
                                <a href="https://valuetop.net/" class="hover:text-gray-500" target="blank">
                                    <span class="font-light">https://www.valuetop.net/</span>
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