<template>

    <v-container rounded="xl">
        <v-row id="ProfileInformation">
            <v-col cols="7" id = ProfileCol>
                Member Since
            </v-col>
            <v-col id = ProfileCol>
                April 2023
            </v-col>
        </v-row>
        <v-row>
            <v-divider></v-divider>
        </v-row>
        <v-row id="ProfileInformation">
            <v-col cols="7" id = ProfileCol>
                Age
            </v-col>
            <v-col id = ProfileCol>
                55
            </v-col>
        </v-row>
        <v-row>
            <v-divider></v-divider>
        </v-row>
        <v-row id="ProfileInformation">
            <v-col cols="7" id = ProfileCol>
                Nationality
            </v-col>
            <v-col id = ProfileCol>
                American
            </v-col>
        </v-row>
        <v-row>
            <v-divider></v-divider>
        </v-row>
        <v-row id="ProfileInformation">
            <v-col cols="8" id = ProfileCol>
                <v-icon icon="mdi-seal" color="green" size="large"></v-icon>
                Super Host
            </v-col>
            <v-col id = ProfileColRight>
                <v-icon icon="mdi-check" color="green"></v-icon>
            </v-col>
        </v-row>
        <v-row>
            <v-divider></v-divider>
        </v-row>
        <v-row id="ProfileInformation">
            <v-col cols="8" id = ProfileCol>
                Trusted Partner
            </v-col>
            <v-col id = ProfileColRight>
                <v-icon icon="mdi-check" color="green"></v-icon>
            </v-col>
        </v-row>
        <v-row>
    
            <v-divider></v-divider>
        </v-row>
        <v-row id="ProfileInformation">
            <v-col cols="8" id = ProfileCol>
                <v-icon icon="mdi-phone"></v-icon>
                Verified Phone Number
            </v-col>
            <v-col id = ProfileColRight>
                <v-icon icon="mdi-check" color="green"></v-icon>
            </v-col>
        </v-row>
        <v-row>
    
            <v-divider inset></v-divider>
        </v-row>
        <v-row id="ProfileInformation">
            <v-col cols="8" id = ProfileCol>
                <v-icon icon="mdi-facebook" color="indigo-darken-1"></v-icon>
                Verified Facebook
            </v-col>
            <v-col id = ProfileColRight>
                <v-icon icon="mdi-check" color="green"></v-icon>
            </v-col>
        </v-row>
    
    
    </v-container>
    
</template>

<style >

.v-list{
    border: 1px solid grey
}

#ProfileInformation{
    padding-top: 4px;
    padding-bottom: 4px;
}

#ProfileCol{
    text-align: left;
    padding-left: 0px;
}

#ProfileColRight{
    text-align: right;
    padding-left: 0px;
}

</style>