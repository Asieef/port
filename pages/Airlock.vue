<template>
    <div class="font-display">
        <div class="h-16 bg-gray-100 text-xl text-[#232323] flex items-center font-semibold font-display px-8">
            <NuxtLink to="/">
                <h2 class="hover:border-b-2 border-[#fecd45]">Home</h2>
            </NuxtLink>
        </div>
        <div>
            <img src="portfolio/airlock-header.jpg" />
        </div>

        <div class="flex justify-center py-12">
            <h2 class="text-3xl flex items-center font-display">Airlock - Responsive HTML Template
            </h2>
        </div>
        <div class="grid grid-cols-2">
            <div class="col-span-1 px-24">
                <p class="text-sm text-[#232323] font-medium leading-7">
                    This template has been made with HTML & CSS only. CSS grid and flex have
                    been used for the structure and aligment of components. Transition with
                    blur effects have also been used.

                <ul class=" list-disc px-4 py-2">
                    <li>Grid </li>
                    <li>Flex</li>
                    <li>Fontawesome</li>
                    <li>Transition</li>
                    <li>Animation</li>
                    <li>Mobile Responsive</li>

                </ul>
                </p>
            </div>

            <div class="col-span-1 text-[#232323] flex justify-center text-sm">
                <div>
                    <ul class="px-20">
                        <li class="border-b border-[#fecd45] pb-4">
                            <h2 class="font-semibold">
                                Core Technologies :
                                <span class="font-light">HTML, CSS</span>
                            </h2>
                        </li>

                        <li class="border-b border-[#fecd45] py-4">
                            <h2 class="font-semibold">
                                Features :
                                <span class="font-light">Mobile Responsive,CSS,Transition</span>
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
                                <a href="https://asieef.github.io/Air-Lock/" class="hover:text-gray-500" target="blank">
                                    <span class="font-light">https://asieef.github.io/Air-Lock/</span>
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