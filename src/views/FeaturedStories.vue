<script setup>
import FeaturedStoriesGrid from '../components/FeaturedStoriesGrid.vue'
</script>

<template>
    <div class="featuredHeader">
        <h1>Featured Stories</h1>
        <!-- TODO build the story grid as a separate component -->
        <!-- Basically it will have a gridItem with 4 div boxes -->
        <!-- In the current FeaturedStores file we will loop JSON from the backend -->
        <!-- Then add data to the gridItem components -->
        <FeaturedStoriesGrid />
        
    </div>
    
</template>

<style>
.featuredHeader {
    margin-top: 12%;
    margin-right: 39%;
    margin-left: 42%;
    color: white;
}
</style>
