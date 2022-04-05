<template>
  <div class="container">
    <div class="title">
      <h5>Testimonials</h5>
      <hr />
    </div>
    <div class="slogan"><h6>WHAT'S THE CUSTOMER SAY ABOUT OUR WORK</h6></div>
    <div class="testimonial">
      <div class="testimonial-conteiner">
        <div class="constumers-widget">
          <div class="widget-text">
            <p>
              When, while lovely valley teems with vapour around meand eridian
              sun strikes the upper impenetrable foliage of my trees, and but a
              thousand unknown plants are noticed by when I hear the buzz of the
              little
            </p>
            <h5>Viviana Lorem</h5>
            <h6>Amazon</h6>
          </div>
          <img src="../../public/img/oliver-ragfelt-488196-2.jpg" alt="" />
        </div>
        <div class="constumers-widget">
          <div class="widget-text">
            <p>
              When, while lovely valley teems with vapour around meand eridian
              sun strikes the upper impenetrable foliage of my trees, and but a
              thousand unknown plants are noticed by when I hear the buzz of the
              little
            </p>
            <h5>Viviana Lorem</h5>
            <h6>Amazon</h6>
          </div>
          <img src="../../public/img/oliver-ragfelt-488196-2.jpg" alt="" />
        </div>
        <div class="constumers-widget">
          <div class="widget-text">
            <p>
              When, while lovely valley teems with vapour around meand eridian
              sun strikes the upper impenetrable foliage of my trees, and but a
              thousand unknown plants are noticed by when I hear the buzz of the
              little
            </p>
            <h5>Viviana Lorem</h5>
            <h6>Amazon</h6>
          </div>
          <img src="../../public/img/oliver-ragfelt-488196-2.jpg" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TestimonialPh",
};
</script>

<style lang="scss" scoped>
.container {
  padding: 0 0 0 15rem;
  background-image: url("../../public/img/7576.svg");
  background-size: cover;
  background-color: #1f1e38;
  &::after {
    content: "";
    clear: both;
    display: table;
  }
}
.title {
  width: 100%;
  padding: 2rem 15rem 0 0;
  h5 {
    text-align: center;
    text-transform: uppercase;
    color: #aaa;
    font-weight: 200;
  }
  hr {
    color: #3affbf;
    width: 2rem;
    border: 2px solid;
    margin-right: 0.5rem;
    float: right;
  }
  &::after {
    content: "";
    clear: both;
    display: table;
  }
}
.slogan {
  width: 58%;
  float: right;
  padding: 1rem 15rem 1rem 0;
  text-align: end;
  h6 {
    color: #fff;
    font-size: 2rem;
    font-weight: 600;
  }
}

.testimonial {
  width: 100%;
  padding: 1rem 1rem 0 1rem;
  background-color: #fff;
  display: flex;
  flex-direction: column;
  justify-content: center;
  .testimonial-conteiner {
    width: 100%;
    padding: 0 15rem 0 0;
    display: flex;
    .constumers-widget {
      width: calc(100% / 3);
      position: relative;
      img {
        width: 100%;
        visibility: hidden;
      }
      &:hover img {
        visibility: visible;
      }

      &:hover .widget-text p,
      &:hover .widget-text h5,
      &:hover .widget-text h6 {
        color: #fff;
      }
      .widget-text {
        position: absolute;
        padding: 1.5rem;
        p {
          margin-bottom: 2rem;
        }
        h5 {
          font-weight: 600;
          font-size: 1.5rem;
        }
        h6 {
          font-weight: 400;
        }
      }
    }
  }
}
</style>
