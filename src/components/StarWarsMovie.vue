<template>
        <v-card>
            <v-card-title>
                <div>
                    <h3> {{ film.title }} </h3>
                </div>
                <div>
                    <p> Released: {{ film.release_date }}</p>
                </div>
            </v-card-title>
        </v-card>
        
</template>

<script>

export default {
    props: ["film"],
}
</script>

<style scoped>

</style>