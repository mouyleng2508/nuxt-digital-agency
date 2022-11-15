<template>
  <div
    class="
      w-full
      border
      py-6
      px-12
      flex
      rounded-md
      shadow-md shadow-secondary
      justify-between
      bg-white
    "
  >
    <div
      v-for="(l, i) in logoItems"
      :key="i"
      class="flex items-center space-x-3"
    >
      <div>
        <img
          class="object-contain h-8 w-8 rounded-full"
          :src="`${l.logo}`"
          alt=""
        />
      </div>
      <div class="capitalize font-bold text-primary hidden md:block">
        {{ l.title }}
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      logoItems: [
        {
          logo: "/linkedin.png",
          title: "Linkedin",
        },
        {
          logo: "/pinterest.png",
          title: "Pinterest",
        },
        {
          logo: "/fb.png",
          title: "Facebook",
        },
        {
          logo: "/apple.png",
          title: "Apple",
        },
        {
          logo: "/slack.jpeg",
          title: "Slack",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
</style>