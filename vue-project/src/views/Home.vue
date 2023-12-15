<script setup>
const intro = [{
    name: '< nikojan >',
    title: 'Aspiring FRONTEND DEVELOPER, UI/UX DESIGNER, QA ANALYST',
    subtext: 'a computer science student that has worked on multiple academic projects involving user interfaces & front-end development.'
}]
</script>

<template>
        <!-- To do: PARALLAX effect -->
        <div class="parallax-holder">
            <img src="../assets/img/pexels-miguel-á-padriñán-194096.jpg" alt="" class="background">
            <img src="../assets/img/hold-coffee.png" alt="" class="foreground">
                        
            <div class="home-text container-lg text-white px-4 md:px-8">
                <div id="home-left">
                    <h1 class="home-name font-Poppins font-bold tracking-widest text-center text-4xl md:text-5xl lg:text-7xl md:text-left">{{ intro[0].name }}</h1>
                    <h3 class="career-title text-center md:text-left text-2xl">{{ intro[0].title }}</h3>
                    <hr>
                    <p class=" text-center md:text-left">{{ intro[0].subtext }}</p>
                </div>
            </div>
        </div>
</template>
    