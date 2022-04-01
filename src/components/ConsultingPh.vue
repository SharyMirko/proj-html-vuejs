<template>
  <div class="container">
    <div class="title">
      <h2>OUR CONSULTANTS CAN HELP YOU</h2>
      <hr />
    </div>
    <div class="widget-container">
      <div class="column">
        <div class="widget-box">
          <div class="widget-icon">A</div>
        </div>
      </div>
      <div class="column"></div>
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
  padding: 5rem 0 0 10rem;
}
.title {
  height: 2rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  hr {
    color: #3affbf;
    width: 60%;
    border: 2px solid;
  }
}
.widget-container {
  display: flex;
  .column {
    margin: 3rem 0;
  }
}

.widget-icon {
  width: 54px;
  height: 54px;
  border-radius: 100%;
  background-color: #f81e3a;
  text-align: center;
  line-height: 3.3;
}
</style>
