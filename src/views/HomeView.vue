<script setup>
import TheHero from '@/components/TheHero.vue'
import HomeCards from '@/components/HomeCards.vue'
import JobListings from '@/components/JobListings.vue'
</script>

<template>
    <TheHero />
    <HomeCards />
    <JobListings :limit="3" :showButton="true" />
</template>
