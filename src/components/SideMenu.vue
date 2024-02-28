<template>
    
        <v-container class="fill-height">
            <v-responsive class=" text-center fill-height">
                <v-row class="d-flex align-center justify-center">
                    <v-col cols="auto" style="width: 350px;">
                        <Profile/>
                    </v-col>
                </v-row>
                <v-row class="d-flex  justify-center">
                    <v-col cols="auto">
                        <Socials/>
                    </v-col>
                </v-row>
                <v-row class="d-flex  justify-center" v-show="displayAwards">
                    <v-col cols="auto">
                        <AwardsSection/>
                    </v-col>
                </v-row>
                <v-row class="d-flex justify-center">
                    <v-col cols="auto">
                        <v-btn elevation="0">
                            Report    
                            <v-icon size="30px" color="blue-grey-darken-3">mdi-flag</v-icon>
                        </v-btn>
                    </v-col>
                </v-row>
		    
                
            </v-responsive>
        </v-container>
</template>


<script lang="ts" setup>
  import Socials from '@/components/SideMenu/Socials.vue'
  import Profile from '@/components/SideMenu/Profile.vue'
  import AwardsSection from '@/components/SideMenu/AwardsSection.vue'

  
  
  import { computed } from 'vue'
  import { useDisplay } from 'vuetify'

  const { name } = useDisplay()

  const displayAwards = computed(() => {
    // name is reactive and
    // must use .value
    switch (name.value) {
      case 'xs': 
      case 'sm': 
      case 'md': 
          return false
      case 'lg': 
      case 'xl': 
      case 'xxl': 
          return true
    }
    console.log(name.value)
    return undefined
  })
</script>