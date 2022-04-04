<template>
  <div class="container">
    <div class="jumbo-about"></div>
    <div class="slogan-about">
      <div class="title"><h6>about us</h6></div>
      <div class="slogan">
        <h5>WE MAKE YOUR STRATEGY WORK</h5>
      </div>
      <div class="slogan-text">
        <p>
          When, while lovely valley teems with vapour around meand eridian sun
          strikes the upper impenetrable foliage of my trees, and but a thousand
          unknown plants are noticed when I hear the buzz of the little world
          among the stalks,and grow familiar indescribable forms of the insects
          .and flies, then I feel the presence of the Almighty .
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutPh",
};
</script>

<style lang="scss" scoped>
.container {
  padding: 0rem 15rem 0 0;
  display: flex;
  background-image: url("../../public/img/7576.svg");
  background-size: cover;
  background-position: right;
  background-color: #1f1e38;
}
.jumbo-about {
  background-image: url("../../public/img/business-people-working-together-on-project-and-5FHSKBL.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  width: 50%;
  height: 500px;
}
.slogan-about {
  width: 50%;
  padding: 3rem 0 0 5rem;
}
</style>
