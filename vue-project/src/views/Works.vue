<script setup>
    import ProjectPlaceholder from '../components/ProjectPlaceholder.vue'

    const works =[
        {
        image:'src/assets/img/mfmf-internship.png',
        title: 'Mafumafu Website Design' ,
        description: 'From my internship, we have been tasked to create a portfolio for a music artist that we listen to. I chose Mafumafu, a Japanese singer, vocalist, and lyricist. This website design is inspired by how mysterious, transcendal, or other wordly his songs seem to be or means. It also reflects the mysterious vibe he gives.'
        },
        {
        image:'src/assets/img/kemrie-internship.png',
        title: 'Kemrie Website Design' ,
        description: 'As part of the final output for our internship, our supervisor assigned us to create a UI/UX design for Kemrie Barcenas. This is a work by pair and I spearheaded the utilization of technologies for this project and provided support in troubleshooting of the dependencies used. Unlike the former tasks, we have been given a color palette to work on. Regularly, feedbacks are given and the design is updated based from these.'
        },
]

</script>

<template>
    <section class="bg-white md:px-16 px-8 md:py-24 py-20">
        <ProjectPlaceholder :works="works"/>
    </section>
    
</template>