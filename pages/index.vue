<template>
  <div>
    <Header></Header>
    <div class="demo"></div>
  </div>
</template>

<script>
import Header from '../components/Header'

export default {
  components: {
    Header,
  },
}
</script>
<style lang="scss" scoped>
.demo {
  height: 2000px;
}
</style>
