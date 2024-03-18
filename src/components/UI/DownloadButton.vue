<script setup>
import { IconDownload } from '@/helpers/icon';


const props = defineProps({
    text: String,
})

</script>

<template>
    <button class="download__btn">
        <div class="downlaod__btn-in">
            <IconDownload :size="40" :color="'white'" />
            <h4 class="download__btn-txt"><slot/>{{ text }}</h4>
        </div>
        <div class="download__btn-bg1"></div>
        <div class="download__btn-bg2"></div>
    </button>


</template>

<style lang="scss" scope>
.download__btn {
    background: #F68DFF;
}
</style>