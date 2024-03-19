<script setup>
import { SkillsOnIcon, SkillsOffIcon } from '@/helpers/icon';
</script>

<template>
    <section class="skills">
        <div class="container">
            <h2 class="skills__title">my skills</h2>
            <div class="blocks">
                <div class="blocks__left">
                    <div class="block">
                        <div class="block__title">Css</div>
                        <div class="block__images">
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOffIcon />
                        </div>
                    </div>
                    <div class="block">
                        <div class="block__title">Bootstrap</div>
                        <div class="block__images">
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                        </div>
                    </div>
                    <div class="block">
                        <div class="block__title">JavaScript</div>
                        <div class="block__images">
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                        </div>
                    </div>
                    <div class="block">
                        <div class="block__title">React</div>
                        <div class="block__images">
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                        </div>
                    </div>
                </div>
                <div class="blocks__right">
                    <div class="block">
                        <div class="block__title">Figma</div>
                        <div class="block__images">
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                        </div>
                    </div>
                    <div class="block">
                        <div class="block__title">Tailwind</div>
                        <div class="block__images">
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOffIcon />
                        </div>
                    </div>
                    <div class="block">
                        <div class="block__title">Sass</div>
                        <div class="block__images">
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                            <SkillsOnIcon />
                        </div>
                    </div>
                    <div class="block">
                        <div class="block__title">Node.js</div>
                        <div class="block__images">
                            <SkillsOnIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                            <SkillsOffIcon />
                        </div>
                    </div>        
                </div>
            </div>
        </div>
    </section>
</template>