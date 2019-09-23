<template>
    <v-container>
        <v-row>
            <v-col cols="4" v-for="film in films"
            :key="film.title">
                <star-wars-movie :film="film"></star-wars-movie>
            </v-col>
        </v-row>
    </v-container>
</template>



<script>
import StarWarsMovie from '../components/StarWarsMovie'

export default {
    props: ["films"],
    components: {
        StarWarsMovie
    }
}
</script>

<style scoped>

</style>