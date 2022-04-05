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
    <div class="green-bar">
      <div class="text">
        <div class="text-left">
          <h6>WE HELP TO DELIVER THE BUSINESS CASE</h6>
        </div>
        <div class="text-right">
          <p>
            When, while lovely valley teems with vapour around meand meridian
            sun strikes the upper impenetrable foliage of my trees, and but a
            thousand unknown
          </p>
        </div>
      </div>
      <div class="btn-red"><a href="#">get started</a></div>
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
    width: 25rem;
    padding: 1rem;
    h5 {
      font-size: 2.7rem;
    }
  }
  .slogan-text {
    width: 25rem;
    padding: 0 0 0 1rem;
    font-weight: 200;
    color: #aaa;
    text-align: justify;
  }
}
.green-bar {
  width: 100%;
  padding: 4rem 0 0 0;
  background-color: #35ffbf;
  display: flex;
  flex-direction: column;
  justify-content: center;
  .text {
    display: flex;
    width: 100%;
    padding: 0 5rem;
    .text-left {
      margin: 0 15rem 0 10rem;
      width: 11rem;
      h6 {
        font-weight: 700;
        color: #1f1f39;
        font-size: 1rem;
        line-height: 1.8;
      }
    }
    .text-right {
      width: 20rem;
      font-size: 0.8rem;
      font-weight: 200;
      color: #1f1e38;
    }
  }
}
.btn-red {
  background-color: red;
  padding: 0.8rem 1.4rem;
  align-self: end;
  margin-bottom: 0;
  a {
    color: #fff;
    text-transform: uppercase;
    text-decoration: none;
    display: block;
  }
  &:hover {
    background-color: #1f1e38;
  }
}
</style>
