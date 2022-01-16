<template>
    <!-- <v-container> -->
        <section class="hero">
            <section class="container">
                <v-row dense>
                    <v-col cols="12" md="6">
                        <img id="rounded-card" height="70" src="https://cdn.vuetifyjs.com/images/john.jpg"/>
                            
                        <h1 style="color:white;font-size:2rem;" >Teguh</h1>
                        <h4 style="color:white">Pratu Teguh Ramdani Saputra</h4>
                        <span style="color:white">-</span>
                        <h3 style="color:white;">Putra dari :</h3>
                        <p style="color:white;">Bapak Jaelani & Ibu Sri Sulastri
                        </p>
                    </v-col>

                    <v-col cols="12" md="6">
                        <img id="rounded-card" height="70" src="https://cdn.vuetifyjs.com/images/john.jpg"/>
                            
                        <h1 style="color:white;font-size:2rem;" >Shelvy</h1>
                        <h4 style="color:white">Shelvy Septiarini, S.Psi</h4>
                        <span style="color:white">-</span>
                        <h3 style="color:white;">Putri dari :</h3>
                        <p style="color:white;">Bapak H.Kasan, S.E & Ibu Hj. Sri Mawarti
                        </p>
                    </v-col>
                </v-row>
                
            </section>
        </section>
    <!-- </v-container> -->
    
</template>

<script>
export default {
    name: "Mempelai"
}
</script>

<style>
.hero {
    background: url('../assets/section-mempelai.jpg') no-repeat center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    display: table;
    width: 100%;
}
.hero .container {
    display: table-cell;
    text-align: center;
    vertical-align: middle;
    height: 800px
}
#rounded-card {
  border-radius: 50%; 
  min-height: 10rem;
  min-width: 10rem;
}
</style>