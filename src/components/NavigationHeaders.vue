<script setup>

</script>

<template>
   <header>
      <div class="top-header">
          <div class="left">
            <!-- <img src="../assets/traubco_llc_logo.jpg" /> -->
            <img src="../assets/TraubCo_logo_small.png" />
          </div>
          <div>
            <div>
              <h2 class="headerName">Traubco Inc</h2>
              <h5 class="headerSubName">Cutting Edge Medical Devices</h5>
            </div>
            <div class="aboutUs">
              <nav>
                <RouterLink to="/about">About Us</RouterLink>
              </nav>
            </div>
            <div class="forSales">
              <nav>
                <RouterLink to="/sales">For HealthCare Professionals</RouterLink>
              </nav>
            </div>
            <div class="forPatients">
              <nav>
                <RouterLink to="/patients">For Patients and CareGivers</RouterLink>
              </nav>
            </div>
          </div>
          
      </div>

  </header>
</template>

<style>
img {
  margin-right: 7px;
  margin-top: 0px;
  width: 190px;
  height: 57px;
}
.top-header {
  background-color: #73737733;
  /* background-color: #1d1d1f; */
  /* border: solid 1px #1d1d1f; */
  height: 80px;
}
.left {
  float: left;
  position: relative;
}
.aboutUs {
  float: right;
  margin-right: 2.2em;
  margin-top: -38px;
}
.forSales {
  float: right;
  margin-right: 20.2em;
  margin-top: -38px;
}
.forPatients {
  float: right;
  margin-right: 7.2em;
  margin-top: -38px;
}
a {
  text-decoration: none;
  color: white;
}
.headerName {
  color: white;
}
.headerSubName {
  color: white;
}



/* @media screen and (min-width: 620px) {
  body {
    font-size: 1.9rem;
    line-height: 1.31579;
  }
} */
</style>