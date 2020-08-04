<template>
  <header class="header">
    <b-container fluid class="header-container">
      <b-row align-v="center">
        <b-col>
          <b-icon icon="list"></b-icon>
        </b-col>
        <b-col>
          <router-link to="/">.Pass</router-link>
        </b-col>
        <b-col><b-icon icon="box-arrow-in-right"></b-icon></b-col>
      </b-row>
    </b-container>
  </header>
</template>
<script>
export default {}
</script>
<style lang="scss" scoped>
$pri-color: #41b883;
$scd-color: #35495e;
$w: white;
.header {
  width: 100%;
  background-color: $pri-color;
  text-align: center;
  height: 50px;
  color: $w;
  font-size: 36px;
  &-container {
    height: 50px;
  }
}
</style>
