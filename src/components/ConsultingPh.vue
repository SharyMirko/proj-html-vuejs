<template>
  <div class="container">
    <div class="title">
      <h2>OUR CONSULTANTS CAN HELP YOU</h2>
      <hr />
    </div>
    <div class="widget-container">
      <div class="column">
        <div class="widget-box">
          <div class="widget-icon">
            <img src="../../public/img/diagram-3.svg" alt="" />
          </div>
          <div class="widget-text">
            <h3>STATISTICAL CONSULTING</h3>
            <p>
              When, while lovely valley teems with vapour around meand eridian
              sun strikes the upper impenetrable foliage of my trees, and but a
            </p>
          </div>
        </div>
        <div class="widget-box">
          <div class="widget-icon">
            <img src="../../public/img/wallet2.svg" alt="" />
          </div>
          <div class="widget-text">
            <h3>BANKING CONSULTING</h3>
            <p>
              When, while lovely valley teems with vapour around meand eridian
              sun strikes the upper impenetrable foliage of my trees, and but a
            </p>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="widget-box">
          <div class="widget-icon">
            <img src="../../public/img/megaphone.svg" alt="" />
          </div>
          <div class="widget-text">
            <h3>DIGITAL CONSULTING</h3>
            <p>
              When, while lovely valley teems with vapour around meand eridian
              sun strikes the upper impenetrable foliage of my trees, and but a
            </p>
          </div>
        </div>
        <div class="widget-box">
          <div class="widget-icon">
            <img src="../../public/img/bullseye.svg" alt="" />
          </div>
          <div class="widget-text">
            <h3>ENTERPRISE CONSULTING</h3>
            <p>
              When, while lovely valley teems with vapour around meand eridian
              sun strikes the upper impenetrable foliage of my trees, and but a
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ConsultingPh",
};
</script>

<style lang="scss" scoped>
@import url("../assets/style/parts/_variables.scss");
.container {
  background-color: #fff;
  padding: 5rem 0 0 15rem;
}
.title {
  height: 2rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  hr {
    color: #3affbf;
    width: 65%;
    border: 2px solid;
  }
}
.widget-container {
  display: flex;
  .column {
    display: flex;
    flex-direction: column;
    margin: 4rem 15rem 0 0;
  }
}

.widget-icon {
  width: 54px;
  height: 54px;
  border-radius: 100%;
  background-color: #f81e3a;
  display: flex;
  justify-content: center;
  align-content: center;
  img {
    width: 60%;
  }
}

.widget-box {
  display: -webkit-inline-box;
  width: 20rem;
  margin: 1rem 0 6rem 0;
}

.widget-text {
  h3 {
    margin: 1rem 0;
  }
}
</style>
