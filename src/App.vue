<script setup>
import { RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      YouTube
      <nav>
        <RouterLink to="/">Home</RouterLink>
      </nav>
    </div>
  </header> -->
  <header>
      <div class="top-header">
          <div class="text">Trinbault Corporation</div>
          <!-- Logo -->
          <!-- <div id="logo">
              <img src="../src/assets/logo.png" />
          </div> -->
          
      </div>
      <div id="header-image-menu">
      </div>
  </header>

  

  <RouterView />
</template>

<style scoped>
/* .text {
  position: relative;
  float: left;
  top: -280px;
  left: 10px;
  width: 150px;
  height: 300px;
  padding: 5px;
  border: solid 1px red;
  background: #ffffff;
} */
.top-header {
  height: 7vh;
  overflow: auto;
  margin-top: 1em;
  border: solid 1px red;
}
.text {
  position: sticky;
  /* top: 0px; */
}
</style>
