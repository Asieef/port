<template>
  <div class="font-display">
    <HomeBar />
    <!-- ====== Portfolio Section Start -->
    <section class="pt-8 lg:pt-[40px] pb-12 lg:pb-[40px] mx-8">
      <div class="flex flex-wrap -mx-4">
        <div class="w-full px-4">
          <div class="text-center mx-auto mb-[60px] max-w-[510px]">
            <span class="font-semibold text-lg text-primary mb-2 block">
              Front End Projects
            </span>
            <h2
              class="font-bold text-3xl sm:text-4xl md:text-[40px] text-dark mb-4"
            >
              Recent Projects
            </h2>
            <p class="text-base text-body-color">
              These are some small front end projects implemented with Vue.Js
              framework. Tailwind, Bootstrap have been used for styling
            </p>
          </div>
        </div>
      </div>

      <!-- ====== Cards Section Start -->
      <section class="bg-[#F3F4F6] pt-20 pb-10 lg:pt-[120px] lg:pb-20">
        <div class="container mx-auto">
          <div class="-mx-4 flex flex-wrap">
            <div
              v-for="project in projects"
              :key="project.id"
              class="w-full px-4 md:w-1/2 xl:w-1/3"
            >
              <div class="mb-10 overflow-hidden rounded-lg bg-white">
                <img :src="project.banner" alt="image" class="w-full" />
                <div class="p-8 text-center sm:p-9 md:p-7 xl:p-9">
                  <h3>
                    <a
                      class="text-dark hover:text-primary mb-4 block text-xl font-semibold sm:text-[22px] md:text-xl lg:text-[22px] xl:text-xl 2xl:text-[22px]"
                    >
                      {{ project.title }}
                    </a>
                  </h3>
                  <p class="text-body-color mb-7 text-base leading-relaxed">
                    {{ project.description }}
                  </p>
                  <a
                    :href="project.link"
                    class="text-body-color hover:border-primary hover:bg-primary inline-block rounded-full border border-[#E5E7EB] py-2 px-7 text-base font-medium transition hover:text-gray-600"
                  >
                    View Details
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- ====== Cards Section End -->
    </section>
  </div>
</template>

<script>
import projects from '../data/db.json'

export default {
  data() {
    return {
      projects: [],
    }
  },

  methods: {},
  mounted() {
    this.projects = projects
  },
}
</script>
