<script setup lang="ts">

/*Call Components*/
import Demographics from '@/components/dashboard/Demographics.vue';
import YearlyBreakup from '@/components/dashboard/YearlyBreakup.vue';
import MonthlyEarning from '@/components/dashboard/MonthlyEarnings.vue';
import Cardsapps from '@/components/dashboard/Cardsapps.vue';
import SalesOverview from '@/components/dashboard/SalesOverview.vue';

import RecentTransaction from '@/components/dashboard/RecentTransaction.vue';

import ProductPerformance from '@/components/dashboard/ProductPerformance.vue';
import ProductCards from '@/components/dashboard/ProductCards.vue';
</script>


<template>
    <div class="container">
        <div class="scrollable-column" ref="scrollableColumn">

            <Demographics />
            <YearlyBreakup />

            <ProductCards />
        </div>
        <div class="fixed-column">
            <Cardsapps />
            <MonthlyEarning />
            <YearlyBreakup />
            <SalesOverview />


        </div>

    </div>
</template>



<style>
.container {
    display: flex;
}

.fixed-column {
    flex: 0 0 auto;
    width: 320px;
    padding: 1%;
    /* Ancho deseado de la columna fija */
}

.scrollable-column {
    overflow: auto;
    height: 1220%;
    background-color: lightgray;
}
</style>

