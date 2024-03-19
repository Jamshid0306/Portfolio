<script setup>
import { ref } from 'vue';


const burgermodal = ref(false)

</script>


<template>
    <nav class="nav">
        <RouterLink to="/" class="logo-txt">Jamshid</RouterLink>
        <ul class="nav__items">
            <li class="nav__item"><a href="#scroll_home">home</a></li>
            <li class="nav__item">
                <a href="#scroll_project">
                    projects
                </a>
            </li>
            <li class="nav__item">
                <a href="#scroll_about">about</a>
            </li>
            <li class="nav__item"><a href="#scroll_contact">contact</a></li>
        </ul>
        <ul class="nav__items nav__items2" :class="{ 'active': burgermodal }">
            <li class="nav__item"><a href="#scroll_home">home</a></li>
            <li class="nav__item">
                <a href="#scroll_project">
                    projects
                </a>
            </li>
            <li class="nav__item">
                <a href="#scroll_about">about</a>
            </li>
            <li class="nav__item"><a href="#scroll_contact">contact</a></li>
        </ul>
        <button class="nav__btn"><a class="nav__btn-a" href="#scroll_contact">contact me</a> </button>
        <div class="nav__burger" :class="{ 'activeburger': burgermodal }">
            <div class="nav__burger-btn" :class="{ 'activeburger': burgermodal }" @click="burgermodal = !burgermodal">
                <span></span>
            </div>
        </div>
    </nav>
</template>