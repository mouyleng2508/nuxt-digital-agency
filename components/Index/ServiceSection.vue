<template>
  <div class="lg:h-screen grid lg:grid-cols-2 gap-10 place-items-center px-20">
    <div class="grid lg:grid-cols-2 gap-4">
      <div class="grid lg:grid-rows-2 gap-4">
        <!-- web development -->
        <div class="border p-6 shadow-md rounded-2xl">
          <Code class="h-12 w-12 text-primary" />
          <div class="text-primary font-bold pt-2">
            Web <span class="text-secondary">Developement</span>
          </div>
          <div class="text-xs text-gray-500 pb-5">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit
            quibusdam ut libero?
          </div>
          <button
            class="
              py-2
              px-3
              bg-primary
              text-white
              rounded-full
              flex
              items-center
              space-x-1
            "
          >
            <div class="text-xs">More details</div>
            <Arrow class="h-5 w-5" />
          </button>
        </div>

        <!-- SEO & Marketing -->
        <div class="border p-6 shadow-md rounded-2xl">
          <Check class="h-12 w-12 text-primary" />
          <div class="text-primary font-bold pt-2">
            SEO & <span class="text-secondary">Marketing</span>
          </div>
          <div class="text-xs text-gray-500 pb-5">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit
            quibusdam ut libero?
          </div>
          <button
            class="
              py-2
              px-3
              bg-primary
              text-white
              rounded-full
              flex
              items-center
              space-x-1
            "
          >
            <div class="text-xs">More details</div>
            <Arrow class="h-5 w-5" />
          </button>
        </div>
      </div>

      <div class="grid lg:grid-rows-2 gap-4">
        <!-- UI/UX -->
        <div class="border p-6 shadow-md rounded-2xl">
          <SquareBadge class="h-12 w-12 text-primary" />
          <div class="text-primary font-bold pt-2">
            UI/UX <span class="text-secondary">Analysis</span>
          </div>
          <div class="text-xs text-gray-500 pb-5">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit
            quibusdam ut libero?
          </div>
          <button
            class="
              py-2
              px-3
              bg-primary
              text-white
              rounded-full
              flex
              items-center
              space-x-1
            "
          >
            <div class="text-xs">More details</div>
            <Arrow class="h-5 w-5" />
          </button>
        </div>

        <!-- Graphic Design -->
        <div class="border p-6 shadow-md rounded-2xl">
          <Network class="h-12 w-12 text-primary" />
          <div class="text-primary font-bold pt-2">
            Graphic<span class="text-secondary"> Design</span>
          </div>
          <div class="text-xs text-gray-500 pb-5">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit
            quibusdam ut libero?
          </div>
          <button
            class="
              py-2
              px-3
              bg-primary
              text-white
              rounded-full
              flex
              items-center
              space-x-1
            "
          >
            <div class="text-xs">More details</div>
            <Arrow class="h-5 w-5" />
          </button>
        </div>
      </div>
    </div>
    <div
      class="
        bg-white
        flex flex-col
        justify-center
        items-start
        lg:px-20
        md:px-16
        px-6
        lg:py-16
        pt-44
        text-white
      "
    >
      <div
        data-aos="fade-down"
        data-aos-duration="1900"
        class="text-base text-primary font-bold uppercase"
      >
        Service
      </div>
      <div
        class="font-bold lg:text-4xl text-2xl capitalize py-3 text-secondary"
        data-aos="fade-up"
        data-aos-duration="1900"
      >
        Our Service <br />
        <span class="text-primary font-light">Include.</span>
      </div>
      <div
        class="text-xs text-gray-700"
        data-aos="fade-up"
        data-aos-duration="2900"
      >
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi,
        perferendis quo vel illum officia sunt rem perspiciatis aliquid
        repudiandae molestiae esse! Veniam cum vitae, deleniti nisi natus rerum
        aliquid voluptates.
      </div>
      <div class="pt-4" data-aos="fade-up-left" data-aos-duration="2800">
        <button
          class="
            py-3
            px-6
            flex
            space-x-2
            items-center
            justify-center
            rounded-full
            border border-primary
            hover:bg-primary hover:bg-opacity-10
            shadow-md
          "
        >
          <div class="lg:text-sm text-xs font-semibold text-primary">
            All Services
          </div>
          <div class="bg-primary rounded-full">
            <svg class="h-4 w-4 text-white" viewBox="0 0 24 24">
              <path
                fill="currentColor"
                d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z"
              />
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

<style lang="scss" scoped>
</style>