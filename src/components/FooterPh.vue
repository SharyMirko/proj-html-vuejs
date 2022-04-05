<template>
  <div class="container">
    <div class="jumbo-footer">
      <h6>LET'S TALK ABOUT WORK</h6>
      <p>
        A wonderful serenity has taken possession Far far away, behind the word
        mountains.
      </p>
      <div class="btn"><a href="#">get started</a></div>
    </div>
    <div class="main-footer">
      <img class="img" src="../../public/img/logotype-2-139x23.png" alt="" />
      <ul>
        <li><a href="">menu</a></li>
        <li><a href="">menu</a></li>
        <li><a href="">menu</a></li>
        <li><a href="">menu</a></li>
      </ul>
      <ul class="social">
        <li>
          <a href="#"><img src="../../public/img/instagram.svg" alt="" /></a>
        </li>
        <li>
          <a href="#"><img src="../../public/img/instagram.svg" alt="" /></a>
        </li>
        <li>
          <a href="#"><img src="../../public/img/instagram.svg" alt="" /></a>
        </li>
        <li>
          <a href="#"><img src="../../public/img/instagram.svg" alt="" /></a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterPh",
};
</script>

<style lang="scss" scoped>
.container {
  padding: 10rem 0 0 0;
  background-image: url("../../public/img/7576.svg");
  background-size: cover;
  background-color: #1f1e38;
}
.jumbo-footer {
  width: 100%;
  height: 20rem;
  background-image: url("../../public/img/business-people-working-together-on-project-and-B3MZ4TX.jpg");
  background-size: cover;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  p {
    text-align: center;
    color: #fff;
    width: 25rem;
    margin: 1rem;
  }
  h6 {
    color: #fff;
    font-size: 1.5rem;
    font-weight: 600;
  }
}

.btn {
  background-color: #201e38;
  a {
    color: #fff;
  }
  &:hover {
    background-color: #39febe;
    a {
      color: #201e38;
    }
  }
}

.main-footer {
  padding: 1rem 15rem 1rem 15rem;
  display: flex;
  justify-content: space-between;
  align-content: center;
  .img {
    width: 90px;
    height: 15px;
  }
  .social {
    li {
      margin: 0.2rem;
    }
  }
  ul {
    list-style: none;
    li {
      display: inline;
      margin: 1rem;
      a {
        text-decoration: none;
        text-transform: uppercase;
        color: #aaa;
        font-size: 0.7rem;
        font-weight: 300;
      }
    }
  }
}
</style>
