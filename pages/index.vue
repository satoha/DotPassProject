<template>
  <div>
    <Header></Header>
    <div class="demo"></div>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from '../components/Header'
import Footer from '../components/Footer'
export default {
  components: {
    Header,
    Footer,
  },
}
</script>
<style lang="scss" scoped>
.demo {
  height: 2000px;
}
</style>
