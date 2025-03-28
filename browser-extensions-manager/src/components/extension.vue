<script setup>
defineProps(['name', 'description', 'isActive', 'logo'])
</script>

<template>
    <div class="extension">
        <img :src="'src/'+logo" alt="logo">
        <h1>{{ name }}</h1>
        <p>{{ description }}</p>
    </div>
</template>

<style scoped>
.extension {
    background-color: var(--neutral-900);
    padding: 1em;
    width: max-content;
}
</style>