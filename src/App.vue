<script setup>
import Navbar from './comonents/Navbar.vue';
import Hero from './comonents/Hero.vue';
import HomeCards from './comonents/HomeCards.vue';
import JobListings from './comonents/JobListings.vue';
</script>

<template>
    <Navbar />
    <Hero />
    <HomeCards />
    <JobListings limit="3" show-button="true"/>
</template>