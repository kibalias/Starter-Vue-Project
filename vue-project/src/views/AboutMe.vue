<script setup>
import { Icon } from '@iconify/vue';
const aboutText = 'Performer, critical, and team player on collaborative group projects tasked with leading and assisting building of user interfaces & front-end development, and assuring project requirements are met and functional.';

const icons = ['vscode-icons:file-type-html', 'vscode-icons:file-type-css', 'logos:javascript', 'devicon:tailwindcss', 'logos:bootstrap', 'logos:php', 'devicon:java', 'logos:python', 'logos:mysql', 'devicon:tensorflow']

</script>

<template>
    <section class="aboutMe-section grid lg:grid-cols-12 grid-cols-1 gap-4 lg:px-10 px-8 bg-palette-500 lg:py-32 md:py-24 py-20 text-lg" id="about">
    <div class="left-side lg:col-start-1 lg:col-end-8 lg:pl-20 lg:pr-16 text-justify lg:order-1 order-2">
        <p class="text-palette-300">{{ aboutText }} </p>

        <hr class="lg:mt-8 mt-4">

        <div class="tech-stacks lg:mt-8 mt-4">
            <h1 class="font-bold">Computer Languages and Frameworks</h1>
            <div class="tech-grid grid grid-cols-5 justify-items-center content-center gap-y-3 mt-4">
                <Icon v-for="(icon, index) in icons" :icon="icon" width="60" class="scale-100 hover:scale-150 ease-in duration-300" :key="index" />
            </div>
        </div>
    </div>

    <div class="right-side lg:col-start-9 lg:col-span-3 lg:order-2 order-1">
        <div class="lg:text-right text-center lg:text-8xl text-6xl lg:py-20 font-Bebas">
            ABOUT ME
        </div>
    </div>
</section>
</template>