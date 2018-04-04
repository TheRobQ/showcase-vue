<template>
  <div class="container">
    <Header/>
    <Input/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header'
import Input from './components/Input'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Header,
    Input,
    Footer
  }
}
</script>