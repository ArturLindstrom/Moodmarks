<template>
  <div class="contact">
    <div class="flex">
        <span class="contact">
          Contact Info
        </span>
        <span class="email">
        contact@moodmarks.org
        </span>
        <span class="phone">
        +46 (0) 73 025 91 82
        </span>
      <img src="@/assets/icon-large-mobile.svg" alt="" class="icon-large">
      <span class="info">
        Mood Marks is a typography project created by Isak Hultström Swahn who holds a BFA in Visual Communication from Beckmans School of Design.-)
      </span>
      <img src="@/assets/moodmarks-mobile-small.svg" alt="" width="107px" class="marks">
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="sass" scoped>

.flex
  display: flex
  flex-direction: column
  justify-content: spac-around
  align-items: center
  margin: 6rem 3rem
  
.info, .icon-large, .marks
  text-align: center
  margin: 2rem 0
  
.email, .phone
  align-self: flex-start

.contact
  margin-bottom: 1rem
  align-self: flex-start
</style>