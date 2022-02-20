<template>
  <vueper-slides>
  <vueper-slide v-for="i in 5" :key="i" :image="slide.image" />
  <img src="@/assets/chat-1-1.svg" alt="">
</vueper-slides>
</template>

<script>
import { VueperSlides, VueperSlide } from 'vueperslides'
import 'vueperslides/dist/vueperslides.css'
export default {
  components: { VueperSlides, VueperSlide },
  data(){return{
    slide:{
      image: require('@/assets/chat-1-1.svg')
    }
  }}
}
</script>

<style>

</style>