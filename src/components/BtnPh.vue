<template>
  <div class="btn">{{ text }}</div>
</template>

<script>
export default {
  name: "BtnPh",
  props: {
    text: String,
    link: String,
    color: String,
  },
};
</script>

<style lang="sss" scoped>
.btn {
    padding: 2rem;
    background-color: red;
}
</style>
