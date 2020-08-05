<template>
  <footer class="footer">
    <nav class="footer-blognav">
      <h2>BLOG</h2>
      <b-container fluid>
        <b-row align-v="center">
          <b-col sm="12" md="6" lg="3">
            <div class="footer__nav">憲法</div>
          </b-col>
          <b-col sm="12" md="6" lg="3">
            <div class="footer__nav">民法</div>
          </b-col>
          <b-col sm="12" md="6" lg="3">
            <div class="footer__nav">行政法</div>
          </b-col>
          <b-col sm="12" md="6" lg="3">
            <div class="footer__nav">商法・会社法</div>
          </b-col>
        </b-row>
      </b-container>
    </nav>
    <nav class="footer-appnav">
      <h2>問題集</h2>
      <b-container fluid>
        <b-row align-v="center">
          <b-col sm="12" md="6" lg="3">
            <div class="footer__nav">憲法</div>
          </b-col>
          <b-col sm="12" md="6" lg="3">
            <div class="footer__nav">民法</div>
          </b-col>
          <b-col sm="12" md="6" lg="3">
            <div class="footer__nav">行政法</div>
          </b-col>
          <b-col sm="12" md="6" lg="3">
            <div class="footer__nav">商法・会社法</div>
          </b-col>
        </b-row>
      </b-container>
    </nav>
    <section>
      <b-container fluid>
        <b-row>
          <b-col sm="12"></b-col>
          <b-col sm="12" class="footer__logo">.PassProject</b-col>
          <b-col sm="12">
            &copy; copyrights 2020 satoha all reserved
          </b-col>
        </b-row>
      </b-container>
    </section>
  </footer>
</template>
<style lang="scss" scoped>
$pri-color: #41b883;
$scd-color: #35495e;
$w: white;
.footer {
  text-align: center;
  background-color: $pri-color;
  color: $w;
  &__nav {
    &:hover {
      background-color: $scd-color;
    }
    padding: 5px;
    margin: 10px auto;
    border: solid 1px $w;
    cursor: pointer;
  }
  &__logo {
    font-size: 25px;
    margin-top: 20px;
  }
}
</style>
