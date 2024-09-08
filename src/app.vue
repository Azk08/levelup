<script setup>
import NavigationBar from './component/NavigationBar.vue';
import HeaderPage from './component/HeaderPage.vue';
import AboutPagae from './component/AboutPagae.vue';
import CatalougePage from './component/CatalougePage.vue';
</script>

<template>
    <NavigationBar />
    <header>
        <HeaderPage />
    </header>
    <main>
        <AboutPagae />
    </main>
    <main>
        <CatalougePage />
    </main>
</template>

<style scoped>

</style>