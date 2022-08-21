<template>
<v-card color="#202022" class="rounded-lg" flat>
<v-row>
    <v-col cols="12" sm="4">
        <v-card color="transparent" class="rounded-lg mx-2" flat>
            <v-btn color="green" small>
                <v-icon color="white">far fa-dollar-sign</v-icon>
            </v-btn>
            <h2 class="white--text">$8.77</h2>
            <h6 class="grey--text">Available Balance</h6>
            <v-btn color="#524eed" class="white--text mt-2 whithoutuppercase">Link Account</v-btn>
        </v-card>
    </v-col>
       <v-col cols="12" sm="4">
        <v-card color="#242426" class="rounded-lg mx-2" flat>
            <v-app-bar flat color="rgba(0,0,0,0)">
                <span class="caption grey--text mt-n6">sales</span>
            </v-app-bar>
            <v-app-bar flat color="rgba(0,0,0,0)" class="mt-n12">
                <h4 class=" white--text">96,50%</h4>
                <span class="caption grey--text ml-2">+ 6.7%</span>
            </v-app-bar>
            <v-app-bar flat color="rgba(0,0,0,0)" class="mt-n10">
                <v-progress-linear color="orange" height="6" value="45"></v-progress-linear>
            </v-app-bar>
            <v-card-text class="pt-0 mt-n4">
                <span class="text-caption grey--text font-weight-light">Yearly Goal</span>
            </v-card-text>
        </v-card>
       </v-col>
       <v-col cols="12" sm="4">
        <v-card color="#242426" class="rounded-lg mx-2" flat>
            <v-app-bar flat color="rgba(0,0,0,0)">
                <span class="caption grey--text mt-n6">sales</span>
            </v-app-bar>
            <v-app-bar flat color="rgba(0,0,0,0)" class="mt-n12">
                <h4 class=" white--text">96,50%</h4>
                <span class="caption grey--text ml-2">+ 6.7%</span>
            </v-app-bar>
            <v-app-bar flat color="rgba(0,0,0,0)" class="mt-n10">
                <v-progress-linear color="orange" height="6" value="45"></v-progress-linear>
            </v-app-bar>
            <v-card-text class="pt-0 mt-n4">
                <span class="text-caption grey--text font-weight-light">Yearly Goal</span>
            </v-card-text>
        </v-card>
       </v-col>
</v-row>
</v-card>
</template>

<script>
export default {

}
</script>

<style>

</style>