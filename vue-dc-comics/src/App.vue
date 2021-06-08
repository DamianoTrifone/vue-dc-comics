
<template>
  <div>
    <Header />
    <Content />
    <Footer />
    <SubFooter /> 
    <Cards />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Content from './components/Content.vue'
import Footer from './components/Footer.vue'
import SubFooter from './components/SubFooter.vue'
import Cards from './components/Cards.vue'


export default {
  components: {
    Header,
    Content,
    Footer,
    SubFooter,
    Cards,
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@900&display=swap');

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container{
  width: 70%;
  margin: 0 auto;
}
</style>
