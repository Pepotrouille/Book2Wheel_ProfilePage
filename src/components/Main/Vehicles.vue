<template>
  <v-sheet class="d-flex flex-wrap" width="85%" style="margin-top:20px;">
  

    <VehiclesCard id="VehicleCardStyle"/>
    
    <VehiclesCard id="VehicleCardStyle"/>

    <VehiclesCard id="VehicleCardStyle"/>

    <VehiclesCard id="VehicleCardStyle"/>

    <VehiclesCard id="VehicleCardStyle"/>

    <VehiclesCard id="VehicleCardStyle"/>


    </v-sheet>

    <v-btn width="80%" variant="outlined" color="primary">
      View All vehicles
    </v-btn>

</template>

<style>

#VehicleCardStyle{
  margin:15px;
}
</style>


<script lang="ts" setup>
  import VehiclesCard from "@/components/Main/VehiclesCard.vue";
</script>