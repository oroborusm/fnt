<template>
  <div class="container">
    <div class="row hero">
      <div class="col-sm-12 col-md-6 col-xs-12 align-self-center fadeIn animated">
        <div class="onboard">
          <h1>Una forma <br> <span>simple</span> de <span>invertir</span></h1>
          <p class="quote">( para quienes no aman las finanzas )</p>
        </div>

        <div class="trigger">
          <h3 class="title">Haz crecer tus sueños, Cuéntanos el tamaño de tu inversión.</h3>
          <div class="slide">
            <vue-slide-bar v-model="sliderWithLabel.value" :data="sliderWithLabel.data" :range="sliderWithLabel.range" @callbackRange="callbackRange" :processStyle="sliderCustomzie.processStyle" :lineHeight="sliderCustomzie.lineHeight" :tooltipStyles="sliderCustomzie.tooltipStyles">
              <template slot="tooltip" slot-scope="tooltip" class="tooltip">
              </template>
            </vue-slide-bar>
          </div>
          <div class="inversion">
            <p class="title">Tu inversión es de: <span class="price">${{sliderWithLabel.rangeValue.invers}}</span></p>
          </div>
        </div>
      </div>

      <div class="col-sm-12 col-md-6 col-xs-12">
        <div class="svg">
          <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 520.5 432">
            <defs>
              <pattern id="Nueva_muestra_de_motivo_2" data-name="Nueva muestra de motivo 2" width="51" height="51" patternUnits="userSpaceOnUse" viewBox="0 0 51 51">
                <rect class="cls-1" width="51" height="51"/>
                <rect class="cls-2" width="51" height="51"/>
              </pattern>
            </defs>
            <title>Tienda Fintual</title>
            <g id="Capa_2" data-name="Capa 2">
              <g id="Capa_2-2" data-name="Capa 2">
                <circle class="cls-3 circulo grande slower-extrema animated infinite" cx="163" cy="163" r="163"/>
                <circle class="cls-3 circulo pequeno slower-extrema animated infinite" cx="411" cy="239.5" r="109.5"/>
                <g class="techo">
                  <polygon class="cls-4" points="359.82 233.3 191.42 233.3 206.59 172.62 344.65 172.62 359.82 233.3"/>
                  <g class="bandera blanca">
                    <line class="cls-6" x1="225.56" y1="134.69" x2="225.56" y2="172.62"/>
                    <path class="cls-4" d="M225.56,130.14a26.87,26.87,0,0,1,24.27,4.55c12.14,9.1,22.76,4.55,22.76,4.55s-16.69,18.21-30.35,15.17-16.68,2-16.68,2Z"/>
                  </g>
                  <g class="bandera azul">
                    <line class="cls-6" x1="293.82" y1="134.69" x2="293.82" y2="172.62"/>
                    <path class="cls-5" d="M293.82,130.14a26.89,26.89,0,0,1,24.28,4.55c12.13,9.1,22.75,4.55,22.75,4.55s-16.68,18.21-30.34,15.17-16.69,2-16.69,2Z"/>
                  </g>
                </g>
                <g class="tienda-media">
                  <rect class="cls-4" x="210.39" y="233.3" width="130.47" height="195.7"/>
                  <path class="cls-5" d="M316.58,256.05c0-.08,0-.15,0-.23H237.68c0,.08,0,.15,0,.23a9.1,9.1,0,0,1-9.1,9.11v18.2a9.1,9.1,0,0,1,9.1,9.1c0,.08,0,.16,0,.24h78.91c0-.08,0-.16,0-.24a9.11,9.11,0,0,1,9.1-9.1v-18.2A9.11,9.11,0,0,1,316.58,256.05Z"/>
                </g>
                <g class="tienda-basica bounceInUp animated">
                  <rect class="cls-4" x="187.63" y="315.22" width="119.85" height="113.78"/>
                  <rect class="cls-4" x="254.38" y="377.18" width="38.31" height="36.89"/>
                  <line class="cls-6" x1="273.53" y1="414.07" x2="273.53" y2="378.6"/>
                  <line class="cls-6" x1="255.44" y1="395.62" x2="292.33" y2="395.62"/>
                  <polygon class="cls-5" points="187.63 360.73 163.36 360.73 186.11 309.15 210.39 309.15 187.63 360.73"/>
                  <polygon class="cls-5" points="211.9 360.73 187.63 360.73 210.39 309.15 234.66 309.15 211.9 360.73"/>
                  <polygon class="cls-5" points="236.18 360.73 211.9 360.73 234.66 309.15 258.93 309.15 236.18 360.73"/>
                  <polygon class="cls-5" points="260.45 360.73 236.18 360.73 258.93 309.15 283.2 309.15 260.45 360.73"/>
                  <polygon class="cls-5" points="284.72 360.73 260.45 360.73 283.2 309.15 307.48 309.15 284.72 360.73"/>
                  <rect class="cls-4" x="210.39" y="377.42" width="27.31" height="51.58"/>
                </g>
                <g class="cartel bounceInUp animated delay-mid">
                  <polygon class="cls-5" points="290.79 386.52 322.65 386.52 334.79 429 302.93 429 290.79 386.52"/>
                  <polygon class="cls-4" points="321.13 386.52 289.27 386.52 277.14 429 309 429 321.13 386.52"/>
                </g>
                <line class="cls-4 suelo" x1="55.64" y1="429" x2="474.36" y2="429"/>
                <g class="nube-alta nube-altas animated infinite slower-alta">
                  <path class="cls-7" d="M105.05,100.14A12.81,12.81,0,0,1,92.28,113H45.43a10.94,10.94,0,0,1,.36-21.88,10.05,10.05,0,0,1,1.56.11,6.84,6.84,0,0,1-.06-.91A7,7,0,0,1,58.91,85a17.37,17.37,0,0,1,34.41,2.36A12.8,12.8,0,0,1,105.05,100.14Z"/>
                  <path class="cls-7" d="M45.79,113h0Z"/>
                  <line class="cls-8" x1="26.65" y1="87.28" x2="47.96" y2="87.28"/>
                  <line class="cls-8" x1="13" y1="100.39" x2="34.3" y2="100.39"/>
                </g>
                <g class="nube-alta nube-alta-2 nube-altas animated infinite slower-alta-2">
                  <path class="cls-7" d="M426,84.78a8.69,8.69,0,0,1-8.67,8.69H385.54a7.43,7.43,0,0,1,.25-14.85,7.22,7.22,0,0,1,1,.07c0-.2,0-.41,0-.61a4.75,4.75,0,0,1,7.89-3.56A11.79,11.79,0,0,1,418,76.12,8.69,8.69,0,0,1,426,84.78Z"/>
                  <path class="cls-7" d="M385.79,93.47h0Z"/>
                  <line class="cls-8" x1="372.8" y1="76.05" x2="387.26" y2="76.05"/>
                  <line class="cls-8" x1="363.54" y1="84.95" x2="377.99" y2="84.95"/>
                </g>
                <g class="nube-baja animated infinite slow">
                  <path class="cls-8" d="M489.75,229.55a11.55,11.55,0,1,0-23.09,0H445"/>
                  <line class="cls-8" x1="437.8" y1="229.55" x2="432.02" y2="229.55"/>
                  <line class="cls-8" x1="424.81" y1="229.55" x2="423.36" y2="229.55"/>
                </g>
                <g class="nube-baja animated infinite slower delay-mid">
                  <path class="cls-8" d="M173.75,148.55a11.55,11.55,0,1,0-23.09,0H129"/>
                  <line class="cls-8" x1="121.8" y1="148.55" x2="116.02" y2="148.55"/>
                  <line class="cls-8" x1="108.81" y1="148.55" x2="107.36" y2="148.55"/>
                </g>
                <line class="cls-8 nube-baja animated infinite slower delay-maxium" x1="85.95" y1="203" x2="104" y2="203"/>
                <line class="cls-8 nube-baja animated infinite slower" x1="304.95" y1="110" x2="335" y2="110"/>
                <line class="cls-8 nube-baja animated infinite slower delay-max" x1="232.77" y1="61.64" x2="242" y2="61.64"/>
              </g>
            </g>
            </svg>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import VueSlideBar from 'vue-slide-bar'

export default {
  name: 'HelloWorld',
  components: {
    VueSlideBar
  },
  props: {
    msg: String
  },
  data () {
    return {
      sliderWithLabel: {
        value: 0,
        data: [ 1, 2, 3
        ],
        range: [
          {
            label: '1',
            invers: '100'
          },
          {
            label: '2',
            invers: '200'
          },
          {
            label: '3',
            invers: '300'
          }
        ],
        rangeValue: {}
      },
      sliderCustomzie: {
        val: 3,
        lineHeight: 14,
        processStyle: { 
          backgroundColor: '#1DA9E0' 
        },
        tooltipStyles: { 
          backgroundColor: '#1DA9E0',
          borderColor: '#1DA9E0' 
        }
      }
    }
  },
  methods: {
    callbackRange (val) {
      this.sliderWithLabel.rangeValue = val
      console.log(this.sliderWithLabel.rangeValue)
      //console.log(val)
      if(val.label == 1){
        document.querySelector('.tienda-media').classList.remove('active')
        document.querySelector('.tienda-media').classList.remove('bounceInUp')
        document.querySelector('.tienda-media').classList.remove('animated')
        document.querySelector('.techo').classList.remove('active')
        document.querySelector('.techo').classList.remove('bounceInUp')
        document.querySelector('.techo').classList.remove('animated')
      }else if(val.label == 2){
        //console.log('soy 2')
        document.querySelector('.tienda-media').classList.add('active')
        document.querySelector('.tienda-media').classList.add('bounceInUp')
        document.querySelector('.tienda-media').classList.add('animated')
        document.querySelector('.techo').classList.remove('active')
        document.querySelector('.techo').classList.remove('bounceInUp')
        document.querySelector('.techo').classList.remove('animated')
      }else if (val.label == 3){
        document.querySelector('.tienda-media').classList.add('active')
        document.querySelector('.tienda-media').classList.add('bounceInUp')
        document.querySelector('.tienda-media').classList.add('animated')
        document.querySelector('.techo').classList.add('active')
        document.querySelector('.techo').classList.add('bounceInUp')
        document.querySelector('.techo').classList.add('animated')
        document.querySelector('.bandera').classList.add('active')
        document.querySelector('.bandera').classList.add('bounceInUp')
        document.querySelector('.bandera').classList.add('animated')
      }
    }
  }
}
</script>

<style lang="sass" scoped>
.hero
  //min-height: 90vh
  .onboard
    h1
      color: #4E5D6A
      font-size: 54px
      font-weight: 700
      line-height: 50px
      margin: 0
      span
        color: #1DA9E0
    .quote
      color: #707070
      font-size: 14px
      margin-top: 8px
.svg
  padding: 65px 0
  svg
    max-height: 500px
    &:before
      border-bottom: 6px solid #355080
      content: ''
      display: block
      position: absolute
      width: 100%
  .circulo.grande
    animation-name: circulo-a
  .circulo.pequeno
    animation-name: circulo-b
  .cls-1,
  .cls-6,
  .cls-8
    fill: none
  .cls-2
    fill: #355080
  .cls-3
    fill: #e9f3f6
  .cls-4,
  .cls-7
    fill: #fff
  .cls-4,
  .cls-5,
  .cls-6,
  .cls-7,
  .cls-8
    stroke-linejoin: round
  .cls-4,
  .cls-5,
  .cls-6
    stroke-width: 6px
    stroke: url(#Nueva_muestra_de_motivo_2)
  .cls-5
    fill: #1da9e0
  .cls-7,
  .cls-8
    stroke: #1da9e0
    stroke-width: 4px
  .cls-8
    stroke-linecap: round
  .nube-alta
    animation-name: nubes-altas
  .nube-alta-2
    animation-name: nubes-altas-2
  .nube-baja
    animation-name: nubes
  .techo,
  .tienda-media
    opacity: 0
    //transform: translateY(50px)
    //transition: .25s
    visibility: hidden
  .techo.active,
  .tienda-media.active
    opacity: 1
    //transform: translateY(0)
    visibility: visible

  .techo
    z-index: 1
  .tienda-basica
    z-index: 3
  .tienda-media
    z-index: 2
    
.trigger
  margin-top: 36px
  .slide
    //background: #E9F3F6
    border-radius: 8px
    margin-top: 12px
    padding: 0 4px
    position: relative
    width: 85%
  .title
    color: #4E5D6A
    font-size: 20px
    .price
      color: #1DA9E0
      font-weight: 700
      font-size: 24px
.animated
  animation-duration: 1s
  animation-fill-mode: both

.animated.delay-mid
  animation-delay: .25s
.animated.delay-max
  animation-delay: 1s
.animated.delay-maxium
  animation-delay: 1.5s
.animated.slow
  animation-duration: 10s
.animated.slower
  animation-duration: 15s
.animated.slower-alta
  animation-duration: 30s
.animated.slower-alta-2
  animation-duration: 24s
.animated.slower-extrema
  animation-duration: 100s
.animated.infinite
  animation-iteration-count: infinite

@keyframes bounceInUp
  from,
  60%,
  75%,
  90%,
  to
    animation-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1)
  from
    opacity: 0
    transform: translate3d(0, 3000px, 0)
  60%
    opacity: 1
    transform: translate3d(0, -20px, 0)
  75%
    transform: translate3d(0, 10px, 0)
  90%
    transform: translate3d(0, -5px, 0)
  to
    transform: translate3d(0, 0, 0)

.bounceInUp
  animation-name: bounceInUp

@keyframes nubes
  from
    transform: translateX(-20px)
  50%
    transform: translate(30px)
  100%
    transform: translate(-20px)

@keyframes nubes-altas
  from
    transform: translateX(-5px)
  50%
    transform: translate(200px)
  100%
    transform: translate(-5px)
@keyframes nubes-altas-2
  from
    transform: translateX(-5px)
  50%
    transform: translate(50px)
  100%
    transform: translate(-5px)

@keyframes circulo-a
  from
    transform: translateY(0px)
  50%
    transform: translateY(50px)
  100%
    transform: translateY(0px)
@keyframes circulo-b
  from
    transform: translate(0px)
  50%
    transform: translateY(-70px)
  100%
    transform: translate(0px)
@media (prefers-reduced-motion)
  .animated
    animation: unset !important
    transition: none !important

@media (max-width: 1000px)
  .hero
    margin-top: 36px
    .onboard
      h1
        font-size: 36px
        line-height: 30px
@media (max-width: 590px)
  .trigger
    .slide
      margin: 0 auto
</style>
