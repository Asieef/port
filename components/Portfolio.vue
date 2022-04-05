<template>
    <div class="container mx-auto">
        <div class="flex justify-center items-center mt-10">
            <h2 class="font-display lg:text-[40px] font-light mr-4 text-[#232323]">Project</h2>
            <h2
                class="font-display lg:text-[40px] font-semibold text-[#232323] border-b-2 border-[#fecd45]"
            >Works</h2>
        </div>
        <!-- Wrapper Div -->
        <div class="grid lg:grid-cols-2 mx-4 font-display gap-4 mt-16">
            <!-- Left Panel -->
            <div class="col-span-1">
                <!-- Left Top -->
                <div class="grid grid-rows-2 gap-4">
                    <div class="row-span-1">
                        <div class="grid grid-rows-2 gap-2">
                            <div class="row-span-1">
                                <div class="grid grid-cols-2 gap-4">
                                    <!-- Left Top Left VT -->

                                    <NuxtLink to="/valuetop">
                                        <div
                                            class="col-span-1"
                                            @mouseenter="toggleSpecV"
                                            @mouseleave="toggleSpecV"
                                        >
                                            <div class="relative flex justify-center items-center">
                                                <!-- White Banner  -->

                                                <transition
                                                    enter-active-class="transition ease-out duration-300"
                                                    enter-class="transform opacity-0 scale-95"
                                                    enter-to-class="transform opacity-100 scale-100"
                                                    leave-active-class="transition ease-in duration-75"
                                                    leave-class="transform opacity-100 scale-100"
                                                    leave-to-class="transform opacity-0 scale-95"
                                                >
                                                    <div
                                                        class="absolute bg-white h-5/6 w-5/6 z-10"
                                                        v-if="showSpecV"
                                                    >
                                                        <div
                                                            class="relative bg-white w-full h-full flex justify-center items-center"
                                                        >
                                                            <div class="absolute top-4 right-4">
                                                                <img src="/plus.png" class="h-8" />
                                                            </div>
                                                            <div class="text-center">
                                                                <div>
                                                                    <h2
                                                                        class="text-gray-800 font-medium text-sm"
                                                                    >Value-Top</h2>
                                                                    <h2
                                                                        class="text-gray-600 text-xs py-4"
                                                                    >Website Made With Nuxt.JS</h2>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </transition>

                                                <!-- White Banner Ends -->

                                                <img src="/portfolio/valuetop-banner.jpg" />
                                            </div>
                                        </div>
                                    </NuxtLink>

                                    <!-- Left Top Right Rongta -->

                                    <NuxtLink to="/rongta">
                                        <div
                                            class="col-span-1"
                                            @mouseenter="toggleSpecR"
                                            @mouseleave="toggleSpecR"
                                        >
                                            <div class="relative flex justify-center items-center">
                                                <!-- White Banner  -->

                                                <transition
                                                    enter-active-class="transition ease-out duration-300"
                                                    enter-class="transform opacity-0 scale-95"
                                                    enter-to-class="transform opacity-100 scale-100"
                                                    leave-active-class="transition ease-in duration-75"
                                                    leave-class="transform opacity-100 scale-100"
                                                    leave-to-class="transform opacity-0 scale-95"
                                                >
                                                    <div
                                                        class="absolute bg-white h-5/6 w-5/6 z-10"
                                                        v-if="showSpecR"
                                                    >
                                                        <div
                                                            class="relative bg-white w-full h-full flex justify-center items-center"
                                                        >
                                                            <div class="absolute top-4 right-4">
                                                                <img src="/plus.png" class="h-8" />
                                                            </div>
                                                            <div class="text-center">
                                                                <div>
                                                                    <h2
                                                                        class="text-gray-800 font-medium text-sm"
                                                                    >Rongta</h2>
                                                                    <h2
                                                                        class="text-gray-600 text-xs py-4"
                                                                    >Website Made With Nuxt.JS</h2>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </transition>

                                                <!-- White Banner Ends -->

                                                <img src="/portfolio/rongta-banner.jpg" />
                                            </div>
                                        </div>
                                    </NuxtLink>
                                </div>
                            </div>

                            <!-- Left Middle Tailwind -->

                            <NuxtLink to="tailwind">
                                <div
                                    class="row-span-1"
                                    @mouseenter="toggleSpecT"
                                    @mouseleave="toggleSpecT"
                                >
                                    <div class="relative flex justify-center items-center">
                                        <!-- White Banner  -->

                                        <transition
                                            enter-active-class="transition ease-out duration-300"
                                            enter-class="transform opacity-0 scale-95"
                                            enter-to-class="transform opacity-100 scale-100"
                                            leave-active-class="transition ease-in duration-75"
                                            leave-class="transform opacity-100 scale-100"
                                            leave-to-class="transform opacity-0 scale-95"
                                        >
                                            <div
                                                class="absolute bg-white h-5/6 w-5/6 z-10"
                                                v-if="showSpecT"
                                            >
                                                <div
                                                    class="relative bg-white w-full h-full flex justify-center items-center"
                                                >
                                                    <div class="absolute top-4 right-4">
                                                        <img src="/plus.png" class="h-8" />
                                                    </div>
                                                    <div class="text-center">
                                                        <div>
                                                            <h2
                                                                class="text-gray-800 font-medium text-sm"
                                                            >Tailwind</h2>
                                                            <h2
                                                                class="text-gray-600 text-xs py-4"
                                                            >HTML Template Built With Tailwind</h2>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </transition>

                                        <!-- White Banner Ends -->

                                        <img src="/portfolio/tailwind-banner.jpg" />
                                    </div>
                                </div>
                            </NuxtLink>
                        </div>
                    </div>
                    <!-- Left Bottom -->
                    <NuxtLink to="/galaxy">
                        <div class="row-span-1" @mouseenter="toggleSpecG" @mouseleave="toggleSpecG">
                            <div class="relative flex justify-center items-center">
                                <!-- White Banner  -->

                                <transition
                                    enter-active-class="transition ease-out duration-300"
                                    enter-class="transform opacity-0 scale-95"
                                    enter-to-class="transform opacity-100 scale-100"
                                    leave-active-class="transition ease-in duration-75"
                                    leave-class="transform opacity-100 scale-100"
                                    leave-to-class="transform opacity-0 scale-95"
                                >
                                    <div
                                        class="absolute bg-white h-5/6 w-5/6 z-10"
                                        v-if="showSpecG"
                                    >
                                        <div
                                            class="relative bg-white w-full h-full flex justify-center items-center"
                                        >
                                            <div class="absolute top-4 right-4">
                                                <img src="/plus.png" class="h-8" />
                                            </div>
                                            <div class="text-center">
                                                <div>
                                                    <h2
                                                        class="text-gray-800 font-medium text-sm"
                                                    >Our Galaxy</h2>
                                                    <h2
                                                        class="text-gray-600 text-xs py-4"
                                                    >Template Made With HTML & CSS</h2>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </transition>

                                <!-- White Banner Ends -->

                                <img src="/portfolio/galaxy-banner.jpg" />
                            </div>
                        </div>
                    </NuxtLink>
                </div>
            </div>

            <!-- Right Panel Airlock-->

            <div class="col-span-1">
                <div class="grid grid-rows-2 gap-4">
                    <!-- Right Top -->
                    <NuxtLink to="/airlock">
                        <div class="row-span-1" @mouseenter="toggleSpecA" @mouseleave="toggleSpecA">
                            <div class="relative flex justify-center items-center">
                                <!-- White Banner  -->

                                <transition
                                    enter-active-class="transition ease-out duration-300"
                                    enter-class="transform opacity-0 scale-95"
                                    enter-to-class="transform opacity-100 scale-100"
                                    leave-active-class="transition ease-in duration-75"
                                    leave-class="transform opacity-100 scale-100"
                                    leave-to-class="transform opacity-0 scale-95"
                                >
                                    <div
                                        class="absolute bg-white h-5/6 w-5/6 z-10"
                                        v-if="showSpecA"
                                    >
                                        <div
                                            class="relative bg-white w-full h-full flex justify-center items-center"
                                        >
                                            <div class="absolute top-4 right-4">
                                                <img src="/plus.png" class="h-8" />
                                            </div>
                                            <div class="text-center">
                                                <div>
                                                    <h2
                                                        class="text-gray-800 font-medium text-sm"
                                                    >Airlock</h2>
                                                    <h2
                                                        class="text-gray-600 text-xs py-4"
                                                    >HTML & CSS Template</h2>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </transition>

                                <!-- White Banner Ends -->

                                <img src="/portfolio/airlock-banner.jpg" />
                            </div>
                        </div>
                    </NuxtLink>

                    <!-- Right Bottom Vue -->

                    <NuxtLink to="/vue">
                        <div
                            class="row-span-1"
                            @mouseenter="toggleSpecVue"
                            @mouseleave="toggleSpecVue"
                        >
                            <div class="relative flex justify-center items-center">
                                <!-- White Banner  -->

                                <transition
                                    enter-active-class="transition ease-out duration-300"
                                    enter-class="transform opacity-0 scale-95"
                                    enter-to-class="transform opacity-100 scale-100"
                                    leave-active-class="transition ease-in duration-75"
                                    leave-class="transform opacity-100 scale-100"
                                    leave-to-class="transform opacity-0 scale-95"
                                >
                                    <div
                                        class="absolute bg-white h-5/6 w-5/6 z-10"
                                        v-if="showSpecVue"
                                    >
                                        <div
                                            class="relative bg-white w-full h-full flex justify-center items-center"
                                        >
                                            <div class="absolute top-4 right-4">
                                                <img src="/plus.png" class="h-8" />
                                            </div>
                                            <div class="text-center">
                                                <div>
                                                    <h2
                                                        class="text-gray-800 font-medium text-sm"
                                                    >VUE.JS</h2>
                                                    <h2
                                                        class="text-gray-600 text-xs py-4"
                                                    >Website Made With VUE.JS</h2>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </transition>

                                <!-- White Banner Ends -->

                                <img src="/portfolio/vue-banner.jpg" />
                            </div>
                        </div>
                    </NuxtLink>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    data() {
        return {
            showSpecV: false,
            showSpecR: false,
            showSpecT: false,
            showSpecG: false,
            showSpecA: false,
            showSpecVue: false
        }
    },

    methods: {
        toggleSpecV() {
            this.showSpecV = !this.showSpecV
        },

        toggleSpecR() {
            this.showSpecR = !this.showSpecR
        },

        toggleSpecT() {
            this.showSpecT = !this.showSpecT
        },

        toggleSpecG() {
            this.showSpecG = !this.showSpecG
        },

        toggleSpecA() {
            this.showSpecA = !this.showSpecA
        },

        toggleSpecVue() {
            this.showSpecVue = !this.showSpecVue
        },
    }
}
</script>


<style>
.font-display {
    font-family: "Montserrat";
}
</style>