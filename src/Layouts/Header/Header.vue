<script setup>

import Nav from '@/components/navbar/Nav.vue'

import { IconDownload, GithubIcon, InstagramIcon, LinkedinIcon, FigmaIcon } from "@/helpers/icon"

</script>

<template>
    <header class="header">
        <div class="container">
            <div class="nav-header">
                <Nav />
            </div>
            <div class="blocks">
                <div class="block">
                    <h2 class="name">Jamshid</h2>
                    <h5 class="about__me">I'm front-end web developer</h5>
                    <button class="download__btn">
                        <IconDownload :size="40" :color="'white'" />
                        <h4 class="download__btn">cv</h4>
                    </button>
                </div>
                <div class="links">
                    <GithubIcon :size="40" :color="'black'"/>
                    <InstagramIcon :size="40" :color="'black'"/>
                    <LinkedinIcon :size="40" :color="'black'"/>
                    <FigmaIcon :size="40" :color="'black'"/>
                </div>
            </div>
        </div>
    </header>
</template>