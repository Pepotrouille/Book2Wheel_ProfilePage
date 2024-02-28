<template>
		<v-toolbar color="white" dark fixed app>
		  <v-btn><img src="..\.\assets\Header\b2w-logo.png" id="imgIcons"/></v-btn>
		  
		  <v-spacer />
  
		  <v-btn color="primary">Search Rentals</v-btn>
		  <v-btn color="primary">Contact</v-btn>
  
		  <v-spacer />
  
		  <v-btn color="primary">List your motorbike/car</v-btn>
		  <v-btn><img src="..\.\assets\Header\Currency\Currency_P.png" id="imgIcons" /></v-btn>
		  <v-btn><img src="..\.\assets\Header\Flags\Flag_P.png" id="imgIcons" /></v-btn>
		  <v-btn><v-icon size="large" color="primary">mdi-account-circle-outline</v-icon></v-btn>
		  
		  <!--<v-app-bar-nav-icon color="primary"></v-app-bar-nav-icon>-->
		</v-toolbar>
		
</template>

<style>
v-toolbar{
  font-family: 'Courier New', Courier, monospace;
}

#imgIcons{
  width: auto;
  height: 20px;
}
</style>