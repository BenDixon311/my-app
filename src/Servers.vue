<template>
    
        <v-list>
            <v-list-tile
                    
                    v-for="index in 5"
                    :key="index.title"
                    
                    @click=""
                >

                <v-list-tile-content>
                    <v-list-tile-title>Server #{{index}}</v-list-tile-title>
                </v-list-tile-content>
            </v-list-tile>
        </v-list>
        
     
</template>

<script>
</script>

<style>

</style>
