<script setup>
import NavigationHeaders from '../components/NavigationHeaders.vue'
import FeaturedStories from '../views/FeaturedStories.vue'
import PageFooter from "../components/PageFooter.vue"
import AboutUsMainPageComponent from '@/components/AboutUsMainPageComponent.vue';
</script>

<template>
  <div class="pageMargins">
    <main>
      <div class="mainPageMargins">
        <!-- TODO create one general component for drop down menus
        TODO for each dropdown we will modify that component with data accordingly here -->
        <NavigationHeaders />
        <AboutUsMainPageComponent />
      </div>
      <div>
        <!-- TODO featured stories view -->
        <FeaturedStories />
      </div>
      <div>
        <!-- TODO create grid component or view for other links like jobs or sale information etc -->
      </div>
      <div>
        <!-- TODO footer component -->
        <PageFooter />
      </div>
    </main>
  </div>
</template>

<style>

</style>