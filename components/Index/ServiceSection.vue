<template>
  <div class="lg:h-screen lg:grid lg:grid-cols-2 flex flex-col-reverse gap-10 place-items-center lg:px-20
                  md:px-16
                  px-6 lg:py-0 py-12">
    <div class="grid lg:grid-cols-2 gap-6">
      <div class="grid lg:grid-rows-2 gap-6">
        <!-- web development -->
        <div
          class="border p-6 shadow-md rounded-2xl transform translate-y-3 hover:translate-y-0 duration-500 ease-in-out">
          <Code class="h-12 w-12 text-primary" />
          <div class="text-primary font-bold pt-2">
            Web <span class="text-secondary">Developement</span>
          </div>
          <div class="text-xs text-gray-500 pb-5">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit
            quibusdam ut libero?
          </div>
          <ReusablesButton />
        </div>

        <!-- SEO & Marketing -->
        <div
          class="border p-6 shadow-md rounded-2xl transform translate-y-3 hover:translate-y-0 duration-500 ease-in-out">
          <Check class="h-12 w-12 text-primary" />
          <div class="text-primary font-bold pt-2">
            SEO & <span class="text-secondary">Marketing</span>
          </div>
          <div class="text-xs text-gray-500 pb-5">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit
            quibusdam ut libero?
          </div>
          <ReusablesButton />
        </div>
      </div>

      <div class="grid lg:grid-rows-2 gap-6">
        <!-- UI/UX -->
        <div
          class="border p-6 shadow-md rounded-2xl transform translate-y-3 hover:translate-y-0 duration-500 ease-in-out">
          <SquareBadge class="h-12 w-12 text-primary" />
          <div class="text-primary font-bold pt-2">
            UI/UX <span class="text-secondary">Analysis</span>
          </div>
          <div class="text-xs text-gray-500 pb-5">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit
            quibusdam ut libero?
          </div>
          <ReusablesButton />
        </div>

        <!-- Graphic Design -->
        <div
          class="border p-6 shadow-md rounded-2xl transform translate-y-3 hover:translate-y-0 duration-500 ease-in-out">
          <Network class="h-12 w-12 text-primary" />
          <div class="text-primary font-bold pt-2">
            Graphic<span class="text-secondary"> Design</span>
          </div>
          <div class="text-xs text-gray-500 pb-5">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit
            quibusdam ut libero?
          </div>
          <ReusablesButton />
        </div>
      </div>
    </div>
    <div class="bg-white flex flex-col justify-center items-start lg:px-20 md:px-16 px-0 lg:py-16 text-white">
      <div data-aos="fade-down" data-aos-duration="1900"
        class="md:text-base text-sm text-primary font-semibold uppercase">
        Service
      </div>
      <div class="font-bold lg:text-4xl text-2xl capitalize md:py-3 py-1 text-secondary" data-aos="fade-up"
        data-aos-duration="1900">
        Our Service <br />
        <span class="text-primary font-light">Include.</span>
      </div>
      <div class="text-xs text-gray-700" data-aos="fade-up" data-aos-duration="2900">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi,
        perferendis quo vel illum officia sunt rem perspiciatis aliquid
        repudiandae molestiae esse! Veniam cum vitae, deleniti nisi natus rerum
        aliquid voluptates.
      </div>
      <div class="pt-4" data-aos="fade-up-left" data-aos-duration="2800">
        <button
          class="btn py-3 px-6 flex space-x-2 items-center justify-center rounded-full border border-primary hover:bg-primary hover:bg-opacity-10 shadow-md">
          <div class="lg:text-sm text-xs font-semibold text-primary">
            All Services
          </div>
          <div class="bg-primary rounded-full svg-icon">
            <svg class="h-4 w-4 text-white" viewBox="0 0 24 24">
              <path fill="currentColor" d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z" />
            </svg>
          </div>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
import Code from "~/components/Icons/Code.vue";
import Arrow from "~/components/Icons/Arrow.vue";
import SquareBadge from "~/components/Icons/SquareBadge.vue";
import Check from "~/components/Icons/Check.vue";
import Network from "~/components/Icons/Network.vue";

export default {
  components: { Code, Arrow, SquareBadge, Check, Network },
};
</script>

<style lang="scss" scoped></style>
