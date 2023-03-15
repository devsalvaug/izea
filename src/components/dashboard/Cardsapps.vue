<script setup lang="ts">
import { ref } from 'vue';
import { CircleIcon } from 'vue-tabler-icons';
import { recentTransaction } from '@/data/dashboard/dashboardData';
</script>
<template>
    <v-card class="my-card" prepend-icon="mdi-linkedin">
        <template v-slot:title>
            <p style="color: #047cb4" class="text">Baxtonmiller</p>
        </template>

    </v-card>
    <v-card class="my-card" prepend-icon="mdi-linkedin">
        <template v-slot:title>
            <p style="color: #047cb4" class="text">Baxtonmiller</p>
        </template>

    </v-card>
</template>
<style>
.my-card {
    border-left: 5px solid #047cb4;
    margin: 5%;
}

.text {
    font-size: 70%;

}

.v-icon--prepend {
    color: red;
}
</style>
