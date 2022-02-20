<template>
  <div class="theMarks">
    <section class="main">
      <span>Download four diffrent fonts that supports
        Mood Marks here.-)
      </span>
      <button>DOWNLOAD MOOD MARKS</button>
    </section>
    <section class="paper">
      <span>
        The semicircle resembles the happy smiley when it's turned upwards and the sad smiley when it’s turned downwards. This symbol works as a full stop when written out on its own, but can also be combined with the exclamation mark and the question mark.-)
      </span>
      <button class="read-paper-btn">READ PAPER</button>
      <img src="@/assets/paper.svg" alt="">
    </section>
    <Footer></Footer>
  </div>
</template>

<script>
import Footer from "@/components/Footer.vue"

export default {
  
  components: {Footer}
}
</script>

<style lang="sass" scoped>
  .main 
    height: 90vh
    background: rgba(255, 236, 0, 1)
    display: flex
    flex-direction: column
    justify-content: center
    align-items: center
    padding: 3rem
  
  .paper
    height: 90vh
    display: flex
    flex-direction: column
    justify-content: center
    align-items: center 
    padding: 3rem
    text-align: left

  .read-paper-btn
    margin-top: 2rem
    padding: 1.3rem 4rem

  span
    font-size: 1rem

  button 
    background: black
    color: white
    padding: 1.3rem 1.8rem
    border: none
    margin-top: 1.3rem
</style>