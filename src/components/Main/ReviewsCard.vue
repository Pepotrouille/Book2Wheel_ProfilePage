<template>
    <v-card
    width="100%"
        style="text-align: left;width:100%"
        elevation="0"
      >
        <v-container>
            <v-row>
                <v-col cols="2">
                    <v-avatar class="ma-3" size="50" rounded="20" >
                        <v-img src="https://cdn.vuetifyjs.com/images/cards/halcyon.png"></v-img>
                    </v-avatar>
                </v-col>
                <v-col>
                    <v-row>
                        <v-col cols="8">
                            <span style="color:grey;font-size: 12px;">3 October 2023</span>
                        </v-col>
                        <v-col style="text-align: right;">
                            <span v-for="rankStar in rankStars">
                                <v-icon size="small" :color="rankStar.color">mdi-star</v-icon>
                            </span>
                        </v-col>
                    </v-row>
                    
                    <div style="color:grey;font-size: 15px;"><b>Ron</b> Rented from <b>Rent2Ride</b></div>
                    <div>Good ride Good Owner, good Communication.</div>
                </v-col>
            </v-row>
        </v-container>
      </v-card>
</template>



<script lang="ts" setup>

    const rankStars = [{ color: 'amber' }, { color: 'amber' },{ color: 'amber' },{ color: 'amber' },{ color: 'amber' }]
</script>