<template>
  <div class="container">
    <div class="title">
      <hr />
      <h6>Projects</h6>
    </div>
    <div class="slogan">
      <div class="slogan-text">
        <h6>OUR EXPERT TRUSTED CONSULTANTS HELP CLIENTS</h6>
      </div>
      <div class="slogan-arrow">
        <div class="arrow">
          <img src="../../public/img/arrow-left-short.svg" alt="" />
        </div>
        <div class="arrow">
          <img src="../../public/img/arrow-right-short.svg" alt="" />
        </div>
      </div>
    </div>
    <div class="slider-conteiner">
      <div class="slider-widget">
        <div class="widget-text">
          <h5>Lorem Ipsum</h5>
          <p>Category</p>
        </div>
        <img src="../../public/img/z1el4c4p-790x592.jpg" alt="" />
      </div>
      <div class="slider-widget">
        <div class="widget-text">
          <h5>Lorem Ipsum</h5>
          <p>Category</p>
        </div>
        <img src="../../public/img/z1el4c4p-790x592.jpg" alt="" />
      </div>
      <div class="slider-widget">
        <div class="widget-text">
          <h5>Lorem Ipsum</h5>
          <p>Category</p>
        </div>
        <img src="../../public/img/z1el4c4p-790x592.jpg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ProjectsPh",
  data() {
    return {
      projects: [
        {
          /*    img: link,
          name: text,
          shortTxt: text, */
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.container {
  padding: 0 15rem 0 15rem;
  background-image: url("../../public/img/7576.svg");
  background-size: cover;
  background-color: #1f1e38;
}

.title {
  padding: 2rem 0 0 1rem;
  display: flex;
  align-items: center;
  h6 {
    text-transform: uppercase;
    font-size: 12px;
    color: #fff;
  }
  hr {
    color: #3affbf;
    width: 2rem;
    border: 1px solid;
    margin-right: 0.5rem;
  }
}

.slogan {
  display: flex;
  align-items: center;
  justify-content: space-between;
  h6 {
    font-size: 1.4rem;
    color: #fff;
  }
  .slogan-text {
    width: 45%;
  }
  .slogan-arrow {
    width: 42%;
    display: flex;
    justify-content: end;
  }
}
.arrow {
  width: 30px;
  height: 30px;
  background-color: #36354c;
  margin: 0 0.2rem;
  display: flex;
  justify-content: center;
  align-items: center;
  &:hover {
    background-color: #3affbf;
    cursor: pointer;
  }
}

.slider-conteiner {
  width: 100%;
  display: flex;
  .slider-widget {
    width: calc((100% - 2rem) / 3);
    position: relative;
    margin: 1rem 0.3rem 0 0.3rem;
    img {
      width: 100%;
    }
    .widget-text {
      width: 100%;
      height: 100%;
      position: absolute;
      background-color: rgb(255, 0, 0, 0.6);
      flex-direction: column;
      justify-content: end;
      display: none;
      h5 {
        color: #fff;
        font-weight: 500;
        font-size: 1.3rem;
      }
      p {
        color: #fff;
        font-weight: 300;
        font-size: 0.8rem;
      }
    }
    &:hover .widget-text {
      display: flex;
      cursor: pointer;
    }
  }
}
</style>
