<script setup>
    import { Icon } from '@iconify/vue';

    const props = defineProps([
        'works'
    ])
</script>

<template>
    <div class="grid grid-cols-1 gap-5">
        <div class="project" v-for="(work, index) in works" :key="index">
            <div class="proj-image">
                <img :src="work.image" class="">
            </div>
            <div class="proj-wrapper px-4 w-1/2">
                <div class="proj-title text-3xl font-bold">
                    {{work.title}}
                </div>
                <div class="proj-desc text-base mt-2 text-justify">
                    {{work.description}}
                </div>
                <button id="btn-ui-proj" value="1" class="flex items-center gap-2 bg-gray-500 py-2 px-4 mt-4 rounded-xl text-sm text-white hover:text-gray-100 hover:bg-gray-700">
                    Learn More <Icon icon="formkit:arrowright" style="color: white;" /></button>
            </div>
        </div>
        
    </div>
</template>

<style scoped>
    .project {
        display: flex;
    }

    .proj-image {
        flex: 1;
    }
</style>