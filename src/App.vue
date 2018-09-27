<template>
  <div id="app">
    <div class="cont-hero">
      <Header />
      <Home />
    </div>
    
  </div>
</template>

<script>
import Home from './components/Home.vue'
import Header from './components/Header.vue'

export default {
  name: 'app',
  components: {
    Home, 
    Header
  }
}
</script>

<style lang="sass">
body
  font-family: 'Open Sans', sans-serif
.cont-hero
  //background-image: url('assets/background.svg')
  background-size: 100%
  background-repeat: no-repeat
  background-position: bottom
  height: 100vh
  padding-top: 26px
.vue-slide-bar
  background-color: white !important
  border: 1px solid #1DA9E0
.vue-slide-bar-process
  background: #1DA9E0
.vue-slide-bar-process
  border-radius: 15px
  height: 100%
  left: 0
  position: absolute
  top: 0
  transition: all 0s
  width: 0
  will-change: width
  z-index: 1
.vue-slide-bar-component
  min-height: 92px !important
  padding-top: 16px
.vue-slide-bar-separate-text
  display: none
.vue-slide-bar-tooltip-top
  top: 0 !important
  .vue-slide-bar-tooltip
    background-color: white !important
    border: 8px solid #1DA9E0
    border-radius: 50%
    color: #1DA9E0
    font-weight: 700
    display: block
    line-height: 20px
    height: 40px
    width: 40px
    &:before
      display: none
.vue-slide-bar-range
  left: 2%
  position: absolute
  top: 38px
  width: 96%
  .vue-slide-bar-separate
    background: white
    border: 1px solid #AAAAAA
    border-radius: 50%
    height: 8px
    width: 8px

@keyframes fadeIn 
  from 
    opacity: 0
  
  to 
    opacity: 1
.animated
  animation-duration: 1s
  animation-fill-mode: both
.fadeIn 
  animation-name: fadeIn
</style>
