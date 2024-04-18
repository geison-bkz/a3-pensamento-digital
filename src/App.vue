<script setup>
import { RouterView } from 'vue-router';
import Navbar from '@/components/Navbar.vue';
import DarkModeButton from './components/DarkModeButton.vue';
</script>

<template>
    <Navbar></Navbar>
    <DarkModeButton></DarkModeButton>
    <RouterView />
</template>

<style scoped></style>
