<template>
    <ul>
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/event">Event</NuxtLink></li>
        <li><NuxtLink :to="`/event/${random()}`">Event By id</NuxtLink></li>
    </ul>
</template>

<script setup >
    function random() {
        return Math.floor(Math.random() * 100);
    }
</script>