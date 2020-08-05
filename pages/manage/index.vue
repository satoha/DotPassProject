<template>
  <div>
    <Header></Header>
    <b-container>
      <b-row>
        <b-col sm="4">
          <Mgnav></Mgnav>
        </b-col>
        <b-col sm="8">
          試作中
        </b-col>
      </b-row>
    </b-container>
    <Footer></Footer>
  </div>
</template>
<script>
import Header from '../../components/Header'
import Footer from '../../components/Footer'
import Mgnav from '../../components/Mglobalnav'
export default {
  components: {
    Header,
    Footer,
    Mgnav,
  },
}
</script>
