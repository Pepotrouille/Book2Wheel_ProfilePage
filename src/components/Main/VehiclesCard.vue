<template>

    <v-card
    class="mx-auto"
    width="300"
    max-width="300"
    rounded="xl"
    id="VehicleCard"
    href="https://book2wheel.com/"
    style="text-align: left;
            color: rgb(31, 70, 107);"
    >
    <v-btn id="LikeButton">
        <v-icon>mdi-heart</v-icon>
    </v-btn>
    <v-img src="@/assets/Vehicles/SuzukiScooter.jpg" height="150px" cover ></v-img>

        <v-card-text>
        <b>Yahama Mio</b> | 150 CC
        <br>
        <div id="CardTag">
            <v-icon size="small">mdi-map-marker-outline</v-icon>
            Manilla | 13.1 km
        </div>
        <v-icon color="grey">mdi-star</v-icon>
        <v-icon color="grey">mdi-star</v-icon>
        <v-icon color="grey">mdi-star</v-icon>
        <v-icon color="grey">mdi-star</v-icon>
        <v-icon color="grey">mdi-star</v-icon>
        <span id="CardDescription"> - New Listing</span>
        <br>
        <b>₱ 2,500</b><span id="CardDescription">/day</span>
        </v-card-text>

    </v-card>

</template>

<style>

#LikeButton{
    position: absolute;
    top: 10px;
    left: 10px;
}

#CardDescription{
    color:grey;
}

#CardTag{
    background-color: rgb(205, 220, 223);
    color:rgb(80, 111, 134);
    border-radius: 20px;
    width:fit-content;
    padding-top: 2px;
    padding-bottom: 2px;
    padding-left: 5px;
    padding-right: 5px;
    margin-top: 3px;
    margin-bottom: 8px;
}

</style>