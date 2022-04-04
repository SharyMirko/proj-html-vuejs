<template>
  <header>
    <div class="container">
      <div class="head-side">
        <div class="logo">
          <img src="../../public/img/logotype.png" alt="logo" />
        </div>
        <div class="small-slogan">
          <p>ALWATS THE BEST WAY YOU NEED IT</p>
        </div>
        <div class="large-slogan">
          <h1>THE BEST BUSINESS CONSULTING</h1>
        </div>
        <div class="actions">
          <div class="btn"><a href="#">read more</a></div>
          <div class="btn-play">
            <a href="#"><img src="../../public/img/play-fill.svg" alt="" /></a>
          </div>
        </div>
      </div>

      <div class="head-jumbo">
        <div class="nav">
          <ul>
            <li
              v-for="(item, i) in nav"
              :key="i"
              :class="{ active: activeNav == i }"
            >
              <a
                @click="activeNav = i"
                :href="item.link"
                :style="activeNav == i ? 'color: #fff' : ''"
                >{{ item.name }}</a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderPhlox.vue",
  data() {
    return {
      activeNav: 0,
      nav: [
        {
          name: "Home",
          link: "#",
        },
        {
          name: "About",
          link: "#",
        },
        {
          name: "Projects",
          link: "#",
        },
        {
          name: "Services",
          link: "#",
        },
        {
          name: "Blog",
          link: "#",
        },
        {
          name: "Contact",
          link: "#",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
header {
  height: 680px;
}
.container {
  display: flex;
}
.head-side {
  width: 25%;
  height: 680px;
  background: url("../../public/img/7576.svg");
  background-position: center;
  .logo {
    padding: 0.5rem 4rem;
    img {
      width: 90px;
    }
  }
  .small-slogan {
    padding: 10rem 0 0 9rem;
    p {
      color: white;
      font-weight: 200;
      font-size: 0.8rem;
    }
  }
  .large-slogan {
    width: 30rem;
    margin: 0 0 0 5.6rem;
    position: absolute;
    h1 {
      color: white;
      font-size: 3rem;
      letter-spacing: 5px;
      line-height: 45px;
    }
  }
}
.head-jumbo {
  background-image: url("../../public/img/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  width: 75%;
  height: 680px;
  .nav {
    padding: 0 0 0 30rem;
    ul {
      list-style: none;
      li {
        display: inline-block;
        margin: 0 0.5rem;
        padding: 1rem 0;
        a {
          text-transform: uppercase;
          text-decoration: none;
          color: #aaaaaa;
          font-size: 0.8rem;
          font-weight: 600;
          &:hover {
            color: #fff;
          }
        }
      }
    }
  }
}
.active {
  border-top: 3px solid #fff;
}
.actions {
  display: flex;
  position: relative;
  top: 10rem;
  padding: 0 0 0 5.6rem;
}

.btn-play {
  width: 36px;
  height: 36px;
  border: 1px solid white;
  border-radius: 100%;
  text-align: center;
  line-height: 2.4;
  margin-left: 1rem;
}
.btn-play a {
  display: block;
  text-decoration: none;
}
</style>
