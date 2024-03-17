<script setup>

const props = defineProps({
    text: String,
    default: "CV",
})

</script>

<template>
    <div class="bg1"></div>
    <div class="bg2"></div>
    <button class="download__btn"><slot/>{{ text }}</button>
    
</template>

<style lang="scss" scope>
.download__btn{
    background: #F68DFF;
}
</style>