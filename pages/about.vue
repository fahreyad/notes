<template>
    asd
    <button @click="handleClick">Click Me</button>
</template>

<script setup>
defineAppConfig({
    layout: false
})
function handleClick() {
    setPageLayout('custom')
}
</script>
