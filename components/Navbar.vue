<template>
  <nav id="navbar" class="mynavbar">
    <b-icon icon="x-square-fill" class="mynavbar__close" @click="closeMenu">
    </b-icon>
    <ul type="none" class="mynavbar__list">
      <li class="mynavbar__list--item">
        <b-icon icon="person-plus"></b-icon>
        新規登録
      </li>
      <li class="mynavbar__list--item">
        <b-icon icon="box-arrow-in-right"></b-icon>
        ログイン
      </li>
      <li class="mynavbar__list--item">
        <b-icon icon="box-arrow-left"></b-icon>
        ログアウト
      </li>
      <li class="mynavbar__list--item">
        <b-icon icon="house-door"></b-icon>
        TOP
      </li>
      <li class="mynavbar__list--item">
        <b-icon icon="file-earmark-text"></b-icon>
        ブログ記事
      </li>
      <li class="mynavbar__list--item">
        <b-icon icon="pencil-square"></b-icon>
        問題集アプリ
      </li>
      <li class="mynavbar__list--item">
        <b-icon icon="table"></b-icon>
        学習履歴
      </li>
      <li class="mynavbar__list--item">
        <b-icon icon="gear"></b-icon>
        アカウント
      </li>
      <li class="mynavbar__list--item">
        <b-icon icon="layout-text-window-reverse"></b-icon>
        管理画面
      </li>
    </ul>
  </nav>
</template>
<script>
export default {
  methods: {
    closeMenu() {
      document.getElementById('navbar').style.width = '0'
    },
  },
}
</script>
<style lang="scss" scoped>
$pri-color: #41b883;
$scd-color: #35495e;
$w: white;
.mynavbar {
  height: 100%;
  width: 0;
  position: fixed;
  z-index: 10;
  top: 0;
  left: 0;
  background-color: $scd-color;
  overflow-x: hidden;
  padding-top: 30px;
  transition: 0.5s;
  &__close {
    position: absolute;
    top: 10px;
    left: 200px;
    font-size: 32px;
    margin-left: 50px;
    color: $w;
    cursor: pointer;
  }
  &__list {
    font-size: 28px;
    &--item {
      &:hover {
        background-color: $pri-color;
      }
      cursor: pointer;
      border-bottom: solid 1px $w;
      margin-top: 10px;
    }
  }
  hr {
    color: $w;
  }
}
</style>
