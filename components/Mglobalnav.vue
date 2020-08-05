<template>
  <div role="tablist">
    <b-button v-b-toggle.accordion-1 block variant="info">BLOG管理</b-button>
    <b-collapse
      id="accordion-1"
      visible
      accordion="my-accordion"
      role="tabpanel"
    >
      <b-card>記事一覧</b-card>
      <b-card>新規作成：記事</b-card>
    </b-collapse>
    <b-button v-b-toggle.accordion-2 block variant="info">問題集管理</b-button>
    <b-collapse
      id="accordion-2"
      visible
      accordion="my-accordion"
      role="tabpanel"
    >
      <b-card>コース一覧</b-card>
      <b-card>新規作成：コース</b-card>
    </b-collapse>
    <b-button v-b-toggle.accordion-3 block variant="info">画像管理</b-button>
    <b-collapse
      id="accordion-3"
      visible
      accordion="my-accordion"
      role="tabpanel"
    >
      <b-card>画像一覧</b-card>
      <b-card>新規アップロード</b-card>
    </b-collapse>
    <b-button v-b-toggle.accordion-4 block variant="info">サイト管理</b-button>
    <b-collapse
      id="accordion-4"
      visible
      accordion="my-accordion"
      role="tabpanel"
    >
      <b-card>サイト分析</b-card>
      <b-card>管理者アカウント</b-card>
    </b-collapse>
  </div>
</template>
<style lang="scss" scoped>
$pri-color: #41b883;
$scd-color: #35495e;
$w: white;
button {
  background-color: $scd-color;
  margin-top: 5px;
}
.card {
  &:hover {
    background-color: $pri-color;
  }
  cursor: pointer;
}
</style>
