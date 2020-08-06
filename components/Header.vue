<template>
  <header class="header">
    <Navbar></Navbar>
    <b-container fluid class="header-container">
      <b-row align-v="center">
        <b-col class="header__left">
          <button class="header__menu" @click="openMenu">
            <b-icon icon="list"></b-icon>
          </button>
        </b-col>
        <b-col class="header__center">
          <div class="header__logo">
            <router-link to="/">.Pass</router-link>
          </div>
        </b-col>
        <b-col class="header__right">
          <button class="header__login">
            <b-icon icon="box-arrow-in-right"></b-icon>
            <span class="header__login--font">login</span>
          </button>
        </b-col>
      </b-row>
    </b-container>
  </header>
</template>
<script>
import Navbar from './Navbar'
export default {
  components: {
    Navbar,
  },
  methods: {
    openMenu() {
      document.getElementById('navbar').style.width = '300px'
    },
  },
}
</script>
<style lang="scss" scoped>
$pri-color: #41b883;
$scd-color: #35495e;
$w: white;
@media screen and (max-width: 768px) {
  .header__login--font {
    display: none;
  }
}
.header {
  width: 100%;
  background-color: $pri-color;
  height: 60px;
  color: $w;
  font-size: 36px;
  position: fixed;
  z-index: 200;
  &-container {
    height: 60px;
  }
  &__left {
    text-align: left;
  }
  &__center {
    text-align: center;
  }
  &__right {
    text-align: right;
  }
  a {
    color: $w;
    text-decoration: none;
  }
  &__menu,
  &__login {
    &:hover {
      background-color: $scd-color;
    }
    color: $w;
    font-size: 28px;
    cursor: pointer;
    background-color: transparent;
    border-style: none;
  }
}
</style>
