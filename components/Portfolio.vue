<template>
    <!-- Wrapper Div -->
    <div class="grid grid-cols-2 mx-4 font-display">
        <!-- Left Panel -->
        <div class="col-span-1">
            <!-- Left Top -->
            <div class="grid grid-rows-2">
                <div class="row-span-1">
                    <div class="grid grid-rows-2">
                        <div class="row-span-1">
                            <div class="grid grid-cols-2">
                                <div class="col-span-1 relative flex items-center justify-center">
                                    <transition
                                        enter-active-class="transition ease-out duration-300"
                                        enter-class="transform opacity-0 scale-95"
                                        enter-to-class="transform opacity-100 scale-100"
                                        leave-active-class="transition ease-in duration-75"
                                        leave-class="transform opacity-100 scale-100"
                                        leave-to-class="transform opacity-0 scale-95"
                                    >
                                        <div
                                            class="bg-white h-5/6 w-5/6 absolute z-10 flex justify-center items-center text-center cursor-pointer"
                                            v-if="showSpec"
                                        >
                                            <div>
                                                <h2
                                                    class="text-gray-700 text-sm font-medium"
                                                >Value-Top</h2>
                                                <h2
                                                    class="text-gray-500 text-xs"
                                                >Website Made with Nuxt.JS</h2>
                                            </div>

                                            <img src="/plus.png" class="h-4" />
                                        </div>
                                    </transition>
                                    <Nuxtlink to>
                                        <img src="/valuetop.jpg" @mouseover="toggleSpec" />
                                    </Nuxtlink>
                                </div>

                                <div class="col-span-1 relative flex items-center justify-center">
                                    <!-- <div class="bg-white h-5/6 w-5/6 absolute z-10"></div> -->
                                    <img src="/vue.jpg" />
                                </div>
                            </div>
                        </div>
                        <div class="row-span-1 relative flex items-center justify-center">
                            <!-- <div class="bg-white h-5/6 w-5/6 absolute z-10"></div> -->
                            <img src="/rongta.jpg" />
                        </div>
                    </div>
                </div>
                <!-- Left Bottom -->
                <div class="row-span-1">
                    <img src="/airlock.jpg" />
                </div>
            </div>
        </div>

        <!-- Right Panel -->

        <div class="col-span-1">
            <div class="grid grid-rows-2">
                <div class="row-span-1">
                    <img src="galaxy.jpg" class />
                </div>
                <div class="row-span-1">
                    <img src="tailwind.jpg" />
                </div>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    data() {
        return {
            showSpec: false
        }
    },

    methods: {
        toggleSpec() {
            this.showSpec = !this.showSpec
        }
    }

}
</script>


<style>
.font-display {
    font-family: "Montserrat";
}
</style>