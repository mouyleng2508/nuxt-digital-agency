<template>
  <div class="lg:grid lg:grid-cols-2 h-screen lg:bg-none bg-primary">
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
        class="text-base text-primary capitalize font-bold"
      >
        Best Agency in <span class="text-secondary">Asia</span>
      </div>
      <div
        class="font-bold lg:text-4xl text-2xl capitalize py-3 text-secondary"
        data-aos="fade-up"
        data-aos-duration="1900"
      >
        Digital Agency <br />
        <span class="text-primary font-light">& Solutions.</span>
      </div>
      <div
        class="text-xs text-gray-700"
        data-aos="fade-up"
        data-aos-duration="2900"
      >
        Quick grow your business & boost up sale with professional startup.
      </div>
      <div
        class="pt-4 flex space-x-3"
        data-aos="fade-up-left"
        data-aos-duration="2800"
      >
        <button
          class="
            bg-primary
            py-3
            px-6
            flex
            space-x-2
            items-center
            justify-center
            rounded-full
          "
        >
          <div class="lg:text-sm text-xs font-medium">Get Started</div>
          <div class="bg-white rounded-full">
            <svg class="h-4 w-4 text-primary" viewBox="0 0 24 24">
              <path
                fill="currentColor"
                d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z"
              />
            </svg>
          </div>
        </button>
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
            See Live Demo
          </div>
          <svg class="h-5 w-5 text-primary" viewBox="0 0 24 24">
            <path fill="currentColor" d="M1,21H23L12,2" />
          </svg>
        </button>
      </div>
    </div>
    <div
      class="bg-no-repeat bg-cover bg-left hidden lg:block"
      :style="{
        backgroundImage: ` url('/home.jpg')`,
      }"
    ></div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
</style>