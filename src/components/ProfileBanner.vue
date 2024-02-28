<template>

    <v-container class="mx-auto" width="100%" rounded="0">
        <v-img
        min-height="300px"
        height="300px"
        cover
        src=".././assets/Profile/BlueGradient.jpg"
        >
            <v-container>
                <v-row class="d-flex">
                    <v-col cols="3">
                        <v-avatar color="grey" size="150" rounded="50">
                            <v-img cover src=".././assets/Profile/Portrait.jpg"></v-img>
                        </v-avatar>
                    </v-col>
                    <v-col cols="auto" style="text-align:left;"  id="BannerProfilInfo">
                            <div>
                                Hawar Abdulwahid 
                                <v-icon color="green">mdi-circle</v-icon>
                            </div>
                            <div>
                                <span v-for="rankStar in rankStars">
                                    <v-icon :color="rankStar.color">mdi-star</v-icon>
                                </span>
                            </div>
                            <div>125 Reviews</div>
                            <div>
                                <span v-for="progressBar in progressBars">
                                    <v-icon :color="progressBar.color">mdi-rectangle</v-icon>
                                </span>
                            </div>
                            <div>
                                <b>50%</b> <a href="https://book2wheel.com/">
                                    Complete your Profile  
                                    <v-icon size="large">mdi-chevron-right</v-icon>
                                </a>
                            </div>
                            <div>
                                <div id="SuperHostText" >
                                    Super host are the best and most experiences hosts on Book2Wheel
                                </div>
                                 <a href="https://book2wheel.com/">
                                    <b>read mode</b>
                                    <v-icon size="large">mdi-chevron-right</v-icon>
                                </a>
                            </div>
                    </v-col>
                </v-row>
            </v-container>
        </v-img>
    </v-container>

</template>



<style>
    .v-avatar{
        border: 2px solid darkslategray;
    }

    .v-list-item--density-default.v-list-item--one-line {
        min-height: 20px;
    }

    #BannerProfilInfo div{
        padding-top: 2px;
        padding-bottom: 2px;
    }

    #SuperHostText{
        width:300px;
        color:rgb(97, 120, 120);
    }
</style>



<script lang="ts" setup>

    const rankStars = [{ color: 'yellow' }, { color: 'yellow' },{ color: 'yellow' },{ color: 'grey' },{ color: 'grey' }]
    const progressBars = [{ color: 'green' }, { color: 'green' },{ color: 'grey' },{ color: 'grey' }]
</script>