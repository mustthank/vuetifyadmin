<template>
<div>
    <v-card>
        <v-card-media src="src" height="200px">
        </v-card-media>
        <v-card-title primary-title>
            <div>
                <h3 class="headline mb-0">headline</h3>
                <div>description</div>
            </div>
        </v-card-title>
        <v-card-actions>
            <v-btn flat color="primary">text</v-btn>
            <v-btn @click="logout" flat color="primary">Logout</v-btn>
        </v-card-actions>
    </v-card>
</div>
</template>
<script>
export default {
    methods: {
        
    },
}
</script>
