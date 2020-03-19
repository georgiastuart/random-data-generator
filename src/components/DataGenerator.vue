<template>
    <v-container>
        <v-btn @click="generateRandom()">Generate Random Number</v-btn>

        <div>
            {{ randomNumber }}
        </div>
    </v-container>
</template>

<script>
    export default {
        name: "DataGenerator",
        data: function () {
            return {
                randomNumber: 0
            }
        },
        methods: {
            generateRandom: function () {
                this.randomNumber = Math.random()
            }
        }
    }
</script>

<style scoped>

</style>
