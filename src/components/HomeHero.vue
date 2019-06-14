<template>
    <v-container fluid fill-height class="home-hero">
        <v-layout justify-center align-center column pa-5>
            <div class="display-4 font-weight-black white--text text-xs-center">DICOM</div>
            <div class="display-4 font-weight-black white--text text-xs-center mb-3">medical image in the web</div>
            <div class="display-1 font-weight-bold white--text text-xs-center">website manipulation for medical image</div>
            <v-btn fab class="mt-5 teal lighten-2">
                <v-icon large color="white">expand_more</v-icon>
            </v-btn>
        </v-layout>
    </v-container>
</template>

<script>
    export default {
        name: 'HomeHero'
    };
</script>

<style scoped>
    .home-hero {
        background: url('https://cdn-images-1.medium.com/max/1200/0*-5x8jnxgbSbktTWs.jpg');
        background-size: cover;
        width: 100%;
        height: 50%;
    }
</style>
