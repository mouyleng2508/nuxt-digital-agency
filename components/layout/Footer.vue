<template>
  <div class="border-t-2 border-secondary text-tertiary lg:pt-12 pt-10 lg:px-20 md:px-16 px-6">
    <div class="flex md:flex-row flex-col justify-between lg:py-4 py-6">
      <div class="flex flex-col md:justify-start items-start justify-center">
        <div class="md:mb-3 mb-2 flex items-center">
          <img class="h-12" src="/logo.gif" alt="Digi logo Footer" />
          <div class="uppercase md:text-base text-sm font-bold">Digi</div>
        </div>
        <p class="text-primary font-semibold uppercase text-xs leading-5 text-left">
          Quick grow your business & <br> boost up sale with professional startup
        </p>
      </div>
      <div class="lg:w-3/5 md:w-3/4 mt-10 md:mt-0 md:flex md:justify-end lg:space-x-24 md:space-x-9">
        <div class="flex space-x-20 lg:space-x-24 md:space-x-9">
          <!-- company -->
          <div class="mb-4">
            <h2 class="mb-4 lg:text-base text-sm font-semibold text-tertiary">
              Company
            </h2>
            <ul class="text-tertiary" v-for="(item, n) in navItems" :key="n">
              <NuxtLink :to="`${item.to}`" active-class="text-secondary font-bold" exact="">
                <li class="text-xs text-gray-500 pb-3 hover:underline cursor-pointer capitalize font-semibold">{{
                  item.title }}</li>
              </NuxtLink>
            </ul>
          </div>

          <!-- address -->
          <div class="mb-4 text-tertiary">
            <h2 class="mb-4 lg:text-base text-sm font-semibold">
              Support
            </h2>

            <div class="font-semibold text-gray-500">
              <NuxtLink to="/about" class="text-xs leading-5 hover:underline cursor-pointer">
                About
              </NuxtLink>
            </div>

            <div class="font-semibold text-gray-500">
              <NuxtLink to="/faq" class="text-xs leading-5 hover:underline cursor-pointer">
                FAQ
              </NuxtLink>
            </div>
          </div>
        </div>

        <!-- get in touch -->
        <div class="mb-4  text-gray-500 font-semibold">
          <h2 class="mb-4 text-tertiary lg:text-base text-sm text-primary">
            <!-- {{ $t("nav.contact") }} -->
            Contact
          </h2>

          <div class="text-xs leading-5">+855 (0) 12 345 678</div>

          <a href="mailto:taskforcekh@gmail.com" target="_blank"
            class="text-xs leading-5 hover:underline cursor-pointer">sales@digi.com</a>

          <div class="pt-1 cursor-pointer">
            <div class="font-semibold text-sm py-2 ">
              Digi Business Center
            </div>
            <a class="text-xs hover:underline" href="https://goo.gl/maps/LrR7Mi3Laoi5Kyia6" target="_blank">
              1 Street 96, Phnom Penh
            </a>
          </div>

          <div></div>
        </div>
      </div>
    </div>

    <div class="lg:pt-7 pt-5 py-6 md:flex justify-between items-center md:space-y-0 space-y-2 text-xs">
      <!-- Copy right -->
      <div>© 2023 Digi, Marketing Co, Ltd. All Rights Reserved.</div>

      <!-- social -->
      <div class="hidden md:flex items-center space-x-2">
        <IconsFacebook class="h-6 w-6" />

        <IconsYoutube class="h-6 w-6" />
      </div>

      <!-- developed by -->
      <div class=" text-primary  text-xs">
        Developed by
        <span class="hover:underline font-semibold"><a href="#" target="_blank">Heng
            Mouyleng</a></span>
        Using
        <span class="underline font-semibold "><a href="https://nuxtjs.org/" target="_blank">Nuxtjs</a>
        </span>
        x
        <span class="underline font-semibold"><a href="https://tailwindcss.com/" target="_blank">Tailwind</a></span>
      </div>

      <div class="md:hidden flex items-center space-x-2">
        <IconsFacebook class="h-6 w-6" />

        <IconsYoutube class="h-6 w-6" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {

      navItems: [
        { title: "Home", to: "/" },
        { title: "About", to: "/about" },
        { title: "Our Work", to: "/our_work" },
        { title: "Service", to: "/services" },
      ],
    };
  },
};
</script>

<style lang="scss" scoped></style>
