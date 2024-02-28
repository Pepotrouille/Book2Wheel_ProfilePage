
<template>
	<v-app>

	  <Header />

	  <v-main>
      <v-container>
        <v-responsive id="Menus" class=" fill-height">
          
          <v-row>
            <v-col>

              <ProfileBanner />

            </v-col>
          </v-row>
          <v-row >
            <v-col cols="3" >

              <SideMenu />

            </v-col>
            <v-col >

              <Main />

            </v-col>
          </v-row>
        </v-responsive>
      </v-container>
	  </v-main>
	</v-app>
</template>

<style>
  #Menus{
    align-items: flex-start;
  }
</style>


<script lang="ts">

  import Header from '@/components/Header.vue'
  import ProfileBanner from '@/components/ProfileBanner.vue'
  import SideMenu from '@/components/SideMenu.vue'
  import Main from '@/components/Main.vue'
</script>