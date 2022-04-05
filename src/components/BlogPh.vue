<template>
  <div class="container">
    <div class="title">
      <hr />
      <h6>Blog</h6>
    </div>
    <div class="slogan">
      <h6>THE RECENT NEWS YOU MUST READ IT</h6>
      <div class="btn"><a href="#">view all</a></div>
    </div>
    <div class="blog-container">
      <div class="blog-widget">
        <div class="widget-text">
          <h5>july 4, 2019 by paul</h5>
          <h6>Canadian Consulting Firm acquired by UK Giant</h6>
          <p>
            When, while lovely valley teems with vapour around meand eridian sun
            strikes the upper impenetrable foliage of my trees, and but a ...
          </p>
        </div>
        <img
          src="../../public/img/startup-business-people-and-strategy-board-PAJ3P9K-1390x1042.jpg"
          alt=""
        />
      </div>
      <div class="blog-widget">
        <div class="widget-text">
          <h5>july 4, 2019 by paul</h5>
          <h6>Canadian Consulting Firm acquired by UK Giant</h6>
          <p>
            When, while lovely valley teems with vapour around meand eridian sun
            strikes the upper impenetrable foliage of my trees, and but a ...
          </p>
        </div>
        <img
          src="../../public/img/startup-business-people-and-strategy-board-PAJ3P9K-1390x1042.jpg"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BlogPh",
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
  padding: 2rem 0 0 0;
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
  justify-content: space-between;
  h6 {
    color: #fff;
    font-size: 1.7rem;
    font-weight: 600;
  }
}
.blog-container {
  width: 100%;
  display: flex;
  .blog-widget {
    width: calc((100% - 2rem) / 2);
    margin: 1rem;
    position: relative;
    img {
      width: 100%;
    }
    .widget-text {
      background-color: #fff;
      padding: 2rem;
      position: absolute;
      width: 70%;
      top: 70%;
      left: 30%;
      transform: translate(0%, 10%);
      h5 {
        color: red;
        font-size: 0.6rem;
        font-weight: 200;
      }
      h6 {
        color: #1f1e38;
        font-size: 1rem;
        margin: 0.5rem 0;
      }
      p {
        font-weight: 200;
        font-size: 0.8rem;
      }
    }
  }
}
</style>
