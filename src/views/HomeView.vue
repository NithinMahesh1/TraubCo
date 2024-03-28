<script setup>
import NavigationHeaders from '../components/NavigationHeaders.vue'
import FeaturedStories from '../views/FeaturedStories.vue'
</script>

<template>
  <div class="pageMargins">
    <main>
      <div class="mainPageMargins">
        <!-- TODO create one general component for drop down menus
        TODO for each dropdown we will modify that componet with data accordingly here -->
        <NavigationHeaders />
      </div>
      <div>
        <!-- TODO featured stories view -->
        <FeaturedStories />
      </div>
      <div>
        <!-- TODO create grid component or view for other links like jobs or sale information etc -->
      </div>
    </main>
  </div>
</template>

<style>
.pageMargins {
  /* margin-top: -15px; */
}
.mainPageMargins {

}
</style>