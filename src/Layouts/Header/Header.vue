<script setup>

import Nav from '@/components/navbar/Nav.vue'
import DownloadButton from '@/components/UI/DownloadButton.vue'
import { GithubIcon, InstagramIcon, LinkedinIcon, FigmaIcon } from "@/helpers/icon"

</script>

<template>
    <header class="header">
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
                    <GithubIcon :size="40" :color="'black'" />
                    <InstagramIcon :size="40" :color="'black'" />
                    <LinkedinIcon :size="40" :color="'black'" />
                    <FigmaIcon :size="40" :color="'black'" />
                </div>
            </div>
        </div>
    </header>
</template>