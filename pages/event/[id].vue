<script>
definePageMeta({
    title: 'Event Page',
    layout: 'custom'
})
</script>
<template>
    <div>
        <h1>Event Details</h1>
        <p>This is the event page for event ID: {{ $route.params.id }}</p>
    </div>
</template>