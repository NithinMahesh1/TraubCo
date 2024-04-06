<script setup></script>

<template>
    <div class="featuredStoriesContainer">
        <div class="story1">
            <img class="storyImages storyImage1" src="../assets/coronavirus.jpg" />
            <div class="storyboxText1">
                <p style="font-size: 1.125rem;">Amidst ongoing COVID-19 challenges, TraubCo introduces innovative medical solutions for enhanced safety and efficiency. Click here to discover how our products redefine patient care</p>
            </div>
        </div>

        <div class="story2">
            <img class="storyImages" src="../assets/kyraCleanStirrups.jpg" />
            <div class="storyboxText2">
                <p></p>
            </div>
        </div>

        <div class="story3">
            <img class="storyImages" src="../assets/Urology.jpg" />
            <div class="storyboxText3">
                <p></p>
            </div>
        </div>

        <div class="story4">
            <img class="storyImages" src="../assets/RichardWolfProducts.jpg" />
            <div class="storyboxText4">
                <p></p>
            </div>
        </div>
    </div>
</template>


<style>
.story1 {
    float: left;
    position: relative;
    margin-left: -21em;
    margin-top: 1em;
    background-color: #85bacaea;
}
.story3 {
    float: left;
    position: relative;
    margin-left: -21em;
    margin-top: 12em;
}
.story2 {
    float: right;
    position: relative;
    margin-right: -21em;
    margin-top: 1em;
}
.story4 {
    float: right;
    position: relative;
    margin-right: -21em;
    margin-top: 12em;
}
.storyImages {
  margin-right: 7px;
  margin-top: 0px;
  width: 190px;
  height: 90px;
}
.storyImage1 {
    margin: auto;
    width: 50%;
}
.storyboxText1 {
    /* margin: auto; */
    width: 50%;
}
</style>