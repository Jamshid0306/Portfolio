<script setup>

import Nav from '@/components/navbar/Nav.vue'
import DownloadButton from '@/components/UI/DownloadButton.vue'
import { GithubIcon, InstagramIcon, LinkedinIcon, FigmaIcon } from "@/helpers/icon"

</script>

<template>
    <header class="header" id="scroll_home">
        <div class="container">
            <div class="nav-header">
                <Nav />
            </div>
            <div class="blocks">
                <div class="block">
                    <div class="block__title">
                        <h2 class="name">Jamshid Abdukarimov</h2>
                        <div class="block__title-btn">
                            <h5 class="about__me">I'm a front-end web developer</h5>
                            <DownloadButton :text="'cv'"/>
                        </div>
                    </div>
                </div>
                <div class="links">
                    <GithubIcon class="link" :size="70" :color="'black'" />
                    <InstagramIcon class="link" :size="70" :color="'black'" />
                    <LinkedinIcon class="link" :size="70" :color="'black'" />
                    <FigmaIcon class="link" :size="70" :color="'black'" />
                </div>
            </div>
        </div>
    </header>
</template>