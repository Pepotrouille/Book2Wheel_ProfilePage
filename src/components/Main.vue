<template>
  <v-container class="fill-height">
    <v-responsive class=" fill-height">

      <v-row id="MainElement" class="d-flex justify-center">
        
        <v-btn href="#presonalInfoNav" id="NavButton" value="personalInfo" elevation="0" rounded="0" color="primary">
          <span>Personal Info</span>
          <v-icon>mdi-account-outline</v-icon>
        </v-btn>
        <v-btn href="#vehiclesNav" id="NavButton" value="vehicles" elevation="0" rounded="0" variant="outlined" color="grey-darken-2" >
          <span>Vehicles</span>
          <v-icon>mdi-bicycle</v-icon>
        </v-btn>

        <v-btn href="#locationNav" id="NavButton" value="location" elevation="0" rounded="0" variant="outlined" color="grey-darken-2" >
          <span>Location </span>
          <v-icon>mdi-map-marker-outline</v-icon>
        </v-btn>

        <v-btn href="#reviewsNav" id="NavButton" value="reviews" elevation="0" rounded="0" variant="outlined" color="grey-darken-2" >
          <span>Reviews</span>
          <v-icon>mdi-message-outline</v-icon>
        </v-btn>

        <v-btn href="#awardsNav" id="NavButton" value="awards" elevation="0" rounded="0" variant="outlined" color="grey-darken-2" >
          <span>Awards </span>
          <v-icon>mdi-seal</v-icon>
        </v-btn>
      </v-row>

      <v-row id="MainElement" class="d-flex justify-center" >
          <PersonalInfo id="personalInfoNav" />
      </v-row>
  
      <v-row id="MainElement" class="d-flex justify-center">
          <Vehicles id="vehiclesNav" />
      </v-row>
        
      <v-row id="MainElement" class="d-flex justify-center">
          <Location id="locationNav" />
      </v-row>
        
      <v-row id="MainElement" class="d-flex justify-center">
          <Reviews id="reviewsNav" />
      </v-row>

      <v-row id="MainElement" class="d-flex justify-center">
          <Awards id="awardsNav"/>
      </v-row>
        
    </v-responsive>
  </v-container>
</template>

<style>
  #NavButton{
    width:18%;
  }
  #MainElement{
    margin-top:50px;
  }
  
</style>


<script setup lang="ts">
  import PersonalInfo from '@/components/Main/PersonalInfo.vue'
  import Vehicles from '@/components/Main/Vehicles.vue'
  import Reviews from '@/components/Main/Reviews.vue'
  import Location from '@/components/Main/Location.vue'
  import Awards from '@/components/Main/Awards.vue'



</script>
