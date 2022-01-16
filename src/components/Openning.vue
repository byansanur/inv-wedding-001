<template>
    <v-container class="lighten-5">
        <v-row no-gutters>
            <v-col cols="12" md="6">
                <v-card
                max-width="450"
                >
                    <v-img
                    src="../assets/mock-bg.jpg"
                    max-height="700"
                    max-width="450"
                    class="grey darken-4"
                    ></v-img>
                </v-card>
            </v-col>
            <v-col cols="12" md="6">
                <div class="ex">
                    <h1>We Are Together</h1>
                    <p>“Dan di antara tanda-tanda kekuasaan-Nya ialah Dia menciptakan untukmu pasangan-pasangan dari jenismu sendiri, supaya kamu cenderung dan merasa tenteram kepadanya, dan dijadikan-Nya diantaramu rasa kasih dan sayang. Sesungguhnya pada yang demikian itu benar-benar terdapat tanda-tanda bagi kaum yang berfikir.”</p>
                    <h4>(QS Ar-Rum : 21)</h4>
                </div>
            </v-col>
        </v-row >
        
    </v-container>
</template>

<script>
export default {
    name: "Opening"
}
</script>

<style>
.ex {
    display: table-cell;
    text-align: center;
    vertical-align: middle;
    height: 700px
}
</style>