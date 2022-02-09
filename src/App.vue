<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">
      <img src="./assets/icon-small-mobile.svg" alt="">
      </router-link> 
      <div class="flex">
        <router-link to="/about">About</router-link>
        <router-link to="/contact">Contact</router-link>
        <router-link to="/theMarks">The marks</router-link>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style lang="sass">
@import url('https://fonts.googleapis.com/css2?family=Lexend&display=swap')

*
  margin: 0
  padding: 0

#app 
  font-family: 'Lexend', sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50


#nav 
  padding: 1rem
  display: flex
  justify-content: space-between
  text-transform: uppercase
  align-items: center

  a 
    color: #2c3e50
    margin: 0 .5rem
    text-decoration: none
    font-size: .8rem

    &.router-link-exact-active 
      text-decoration: underline
    
  

</style>
