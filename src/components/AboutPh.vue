<template>
  <div class="container">
    <div class="jumbo-about"></div>
    <div class="slogan-about">
      <div class="title">
        <hr />
        <h6>about us</h6>
      </div>
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
    <div class="nonso"></div>
  </div>
</template>

<script>
export default {
  name: "AboutPh",
};
</script>

<style lang="scss" scoped>
.container {
  padding: 0rem 15rem 5rem 0;
  display: flex;
  flex-wrap: wrap;
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
  color: #fff;
  .title {
    padding: 6rem 0 0 1rem;
    display: flex;
    align-items: center;
    h6 {
      text-transform: uppercase;
      font-size: 10px;
    }
    hr {
      color: #3affbf;
      width: 2rem;
      border: 1px solid;
      margin-right: 0.5rem;
    }
  }
  .slogan {
    width: 20rem;
    padding: 1rem;
    h5 {
      font-size: 2rem;
    }
  }
  .slogan-text {
    padding: 0 0 0 1rem;
    font-weight: 200;
    color: #aaa;
  }
}
.nonso {
  width: 100%;
  height: 10rem;
  background-color: #35ffbf;
}
</style>
