<script setup lang="ts">
import InputText from 'primevue/inputtext';
import ToggleButton from 'primevue/togglebutton';
</script>

<template>
    <div class="p-5 h-screen bg-gray-900 flex items-center justify-center">
        <Button label="Click" />
        <InputText placeholder="Enter your search" />
        <ToggleButton onLabel="On" offLabel="Off" />
    </div>
</template>
