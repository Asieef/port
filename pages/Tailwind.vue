<template>
    <div class="font-display">
               <HomeBar/>
        <div>
            <img src="portfolio/tailwind-header.jpg" />
        </div>

        <div class="flex justify-center py-12">
            <h2 class="lg:text-3xl text-center flex items-center font-display px-4">Tailwind - Responsive Website Built
                With
                Tailwind CSS
            </h2>
        </div>
        <div class="grid lg:grid-cols-2 gap-4 mx-auto container">
            <div class="col-span-1 lg:px-24 px-8">
                <p class="text-sm text-[#232323] font-medium leading-7">
                    This template has been built with Tailwind CSS framework. The site is mobile responsive.
                    Grid & flexboxes have been used throughout for the segmentation and alignment of the
                    layout. Fontawesome icons and svg images have been used.

                <ul class=" list-disc px-4 py-2">
                    <li>Grid </li>
                    <li>Flex</li>
                    <li>Fontawesome</li>
                    <li>SVG images</li>
                    <li>Nuxt JS</li>
                    <li>Hot Reload</li>
                    <li>Fast Load</li>
                    <li>Custom Fonts</li>

                </ul>
                </p>
            </div>

            <div class="col-span-1 text-[#232323] flex justify-center text-sm">
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
                                <span class="font-light">Mobile Responsive, Custom Fonts, Grid, Flex</span>
                            </h2>
                        </li>

                        <li class="border-b border-[#fecd45] py-4">
                            <h2 class="font-semibold">
                                Front-end Tools :
                                <span class="font-light">Tailwind CSS, Illustrator, Photoshop</span>
                            </h2>
                        </li>

                        <li class="border-b border-[#fecd45] py-4">
                            <h2 class="font-semibold">
                                Livedemo :
                                <a href="https://tailwind-blond.vercel.app/" class="hover:text-gray-500" target="blank">
                                    <span class="font-light">https://tailwind-blond.vercel.app/</span>
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