<script setup>
import { IconDownload } from '@/helpers/icon';
const props = defineProps({
    text: String,
})

</script>

<template>
    <a href="/" download="portfolio.pdf" class="download__btn">
            <IconDownload :size="40" :color="'white'" />
            <h4 class="download__btn-txt">
                <slot />{{ text }}
            </h4>
        <div class="download__btn-bg1"></div>
        <div class="download__btn-bg2"></div>
    </a>


</template>

<style lang="scss" scope>
.download__btn {
    position: relative;
    display: flex;
    cursor: pointer;
    align-items: center;
    justify-content: center;
    width: 125px;
    height: 125px;
    color: #fff;
    border-radius: 50%;
    border: none;
    background: #e019e4;

    &-bg1 {
        width: 150px;
        height: 150px;
        position: absolute;
        border-radius: 50%;
        z-index: 2;
        background: rgba(246, 141, 255, 0.36);
    }

    &-bg2 {
        width: 190px;
        height: 190px;
        border-radius: 50%;
        background: rgba(246, 141, 255, 0.36);
        position: absolute;
        z-index: 1;
    }

    &-txt {
        font-family: 'madimi';
        font-weight: 700;
        font-size: 40px;
        letter-spacing: 0.01em;
        text-align: center;
        color: #f5f5f5;
    }
}
</style>