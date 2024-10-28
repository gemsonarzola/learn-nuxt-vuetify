<template>
    <div>
        <v-container>
            <v-btn rounded :loading="loading" color="primary" icon>
                <v-icon>mdi-home</v-icon>
            </v-btn>
        </v-container>
    </div>
</template>
<script setup lang="ts">
const loading = ref(false)

onMounted(() => {
    // loading.value =true
})
</script>