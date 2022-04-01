<template>
  <div class="container">
    <div class="title">
      <h2>OUR CONSULTANTS CAN HELP YOU</h2>
      <hr />
    </div>
  </div>
</template>

<script>
export default {
  name: "ConsultingPh",
};
</script>

<style lang="scss" scoped>
.container {
  background-color: #fff;
  height: 480px;
  display: flex;
}
.title {
  margin: 5rem auto 0 15rem;
  height: 2rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  hr {
    color: #3affbf;
    width: 50%;
    border: 4px solid;
  }
}
</style>
