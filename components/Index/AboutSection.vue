<template>
  <div class="
              h-screen
              grid
              lg:grid-cols-2
              gap-9
              place-items-center
              lg:px-20
              md:px-16
              px-6
              lg:py-16
              pt-44
              bg-blue-50
            ">
    <div class="">
      <div class="md:text-base text-sm text-secondary uppercase font-semibold" data-aos="zoom-in"
        data-aos-duration="1900">
        About us
      </div>
      <div class="font-bold lg:text-4xl text-2xl text-primary capitalize md:py-3 py-2" data-aos="fade-up"
        data-aos-duration="2100">
        Boost <span class=" text-secondary">Your Business</span> <br />
        With Analay
      </div>
      <div class="text-xs text-primary" data-aos="zoom-in" data-aos-duration="2100">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione
        distinctio sed fugiat, id at, mollitia laboriosam placeat nulla earum
        nisi sit assumenda optio in ipsum ex ut provident aliquid dolorem!
      </div>
      <div class="pt-4" data-aos="fade-up-left" data-aos-duration="1800">
        <button class="
                    bg-primary
                    shadow-lg
                    py-3
                    px-6
                    flex
                    space-x-2
                    items-center
                    justify-center
                    text-white
                    rounded-full btn
                  ">
          <div class="text-sm font-medium capitalize">More details</div>

          <svg class="h-5 w-5 text-white svg-icon" viewBox="0 0 24 24">
            <path fill="currentColor" d="M8.59,16.58L13.17,12L8.59,7.41L10,6L16,12L10,18L8.59,16.58Z" />
          </svg>
        </button>
      </div>
    </div>
    <div class="hidden lg:flex items-center lg:space-x-4 space-x-2">
      <div>
        <img class="object-cover w-full shadow-lg rounded-3xl rounded-tr-none" src="/about.jpg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>