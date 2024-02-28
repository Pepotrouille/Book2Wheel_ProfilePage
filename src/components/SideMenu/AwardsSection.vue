<template>
    
    <v-container class="fill-height">
        <v-responsive class="align-center text-center fill-height">
            <v-row class="d-flex align-center justify-center">
                <v-col cols="auto">
                    <h1>Awards Section</h1>
                </v-col>
            </v-row>
            <v-row class="d-flex align-center justify-center">
                <v-col cols="auto">
                    <p id="description">Super hosts are the best and most experienced hosts on Book2Wheel </p>
                    
                </v-col>
            </v-row>
            <v-row class="d-flex align-center justify-center">
                <v-col cols="3">
                    <v-icon icon="mdi-seal" color="yellow-darken-1" size="60px"/>
                </v-col>
                <v-col cols="7">
                    <p id="AwardSection">
                        <a id="AwardTitle">Trusted Partner</a>
                        <br>
                        10 successful rentals
                    </p>
                </v-col>
            </v-row>
            <v-row class="d-flex align-center justify-center">
                <v-col cols="3">
                    <v-icon icon="mdi-seal" color="green-accent-4" size="60px"/>
                </v-col>
                <v-col cols="7">
                    <p id="AwardSection">
                        <a id="AwardTitle">Super Host</a>
                        <br>
                        50 successful rentals
                    </p>
                </v-col>
            </v-row>
            <v-row class="d-flex align-center justify-center">
                <v-col cols="3">
                    <v-icon icon="mdi-seal" color="blue-grey-lighten-2" size="60px"/>
                </v-col>
                <v-col cols="7">
                    <p id="AwardSection">
                        <a id="AwardTitle">Verified Business</a>
                        <br>
                        Provided Business
                    </p>
                    
                </v-col>
            </v-row>
        
            
        </v-responsive>
    </v-container>



</template>

<style>

    #description{
        color:grey;
        font-size: large;
    }

    #AwardTitle{
        font-weight: bold;
    }

    #AwardSection{
        text-align: left;
    }

</style>