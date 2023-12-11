<script setup>
const intro = [{
    name: '< nikojan >',
    title: 'Aspiring FRONTEND DEVELOPER, UI/UX DESIGNER, QA ANALYST',
    subtext: 'a computer science student that has worked on multiple academic projects involving user interfaces & front-end development.'
}]
</script>

<template>
    <section id="home" class="home">
        <!-- To do: PARALLAX effect -->
        <div class="container-lg text-white grid md:grid-cols-12 grid-cols-1 place-content-center px-4 md:px-8">
            <div id="home-left" class="md:col-start-1 md:col-span-7 flex flex-col gap-4">
                <h1 class="home-name text-center font-Poppins font-bold tracking-widest text-4xl md:text-5xl lg:text-7xl">{{ intro[0].name }}</h1>
                <h3 class="career-title">{{ intro[0].title }}</h3>
                <hr>
                <p>{{ intro[0].subtext }}</p>
            </div>
            <div id="home-right" class="md:col-start-8 md:col-span-5">
                Right side
            </div>
        </div>
    </section>
</template>