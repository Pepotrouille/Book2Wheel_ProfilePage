<template>
    <v-container>
        <v-responsive class=" fill-height">
            <v-row style="margin:5px;" class=" justify-center">
                <div style="width: 80%;">
                    <h3>Latest ratings</h3>
                    <v-divider ></v-divider>
                    <ReviewsCard/>
                    <ReviewsCard/>
                    <ReviewsCard/>
                    <ReviewsCard/>
                </div>
            </v-row>
            <v-row style="margin:5px;" class=" justify-center">
                <v-btn variant="outlined" color="primary" width="80%">
                    View all reviews
                </v-btn>
            </v-row>
        </v-responsive>
    </v-container>

</template>

<script lang="ts" setup>
  import ReviewsCard from "@/components/Main/ReviewsCard.vue";
</script>