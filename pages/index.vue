<template>
  <div>
    <div class="relative">
      <Home />

      <SocialSection class="absolute -bottom-9" />
    </div>

    <AboutSection />

    <ServiceSection />
  </div>
</template>

<script>
import Home from "~/components/Index/Home.vue";
import SocialSection from "~/components/Index/SocialSection.vue";
import AboutSection from "~/components/Index/AboutSection.vue";
import ServiceSection from "~/components/Index/ServiceSection.vue";
export default {
  components: { Home, SocialSection, AboutSection, ServiceSection },
  name: "IndexPage",
};
</script>
