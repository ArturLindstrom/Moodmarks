<template>
  <div class="footer">
      <div class="flex">
          <div class="links">
              <router-link to="/">Home</router-link>
              <router-link to="/about">About</router-link>
              <router-link to="/theMarks">The Marks</router-link>
              <router-link to="/contact">Contact</router-link>
          </div>
          <img src="@/assets/moodmarks-mobile-small.svg" alt="">
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
		justify-content: space-between

	.links
		display: flex
		flex-direction: column	

</style>