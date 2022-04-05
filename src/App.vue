<template>
  <div id="app">
    <HeaderPhlox />
    <ConsultingPh />
    <AboutPh />
    <ProjectsPh />
  </div>
</template>

<script>
import HeaderPhlox from "./components/HeaderPhlox.vue";
import ConsultingPh from "./components/ConsultingPh.vue";
import AboutPh from "./components/AboutPh.vue";
import ProjectsPh from "./components/ProjectsPh.vue";
export default {
  name: "App",
  components: {
    HeaderPhlox,
    ConsultingPh,
    AboutPh,
    ProjectsPh,
  },
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Bai+Jamjuree:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;1,200;1,300;1,400;1,500;1,600;1,700&display=swap");
@import url("./assets/style/style.scss");
</style>
