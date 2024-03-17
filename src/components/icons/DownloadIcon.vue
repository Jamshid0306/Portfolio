<script setup>

const props = defineProps({
    size: {
        typeof: Number,
        required: true,
    },
    color: {
        typeof: String,
        required: true,
    }
})

</script>

<template>
    <svg xmlns="http://www.w3.org/2000/svg" :width="size" :height="size" viewBox="0 0 24 24"><path :fill="color" d="M18 15v3H6v-3H4v3c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2v-3zm-1-4l-1.41-1.41L13 12.17V4h-2v8.17L8.41 9.59L7 11l5 5z"/></svg>
</template>