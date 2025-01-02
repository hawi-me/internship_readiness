<script setup>
import { defineProps } from 'vue';
defineProps({
title:{
    type: String,
    default: 'became freelacer developer',
},
subtitle: {
    type: String,
    default: 'find frontend jobs easily',
},
});
</script>
<template>
    <section class="bg-green-700 py-20 mb-4">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col items-center">
            <h1 class="text-4xl text-white font-bold mb-4">Became a Frontend Developer </h1>
            <p class="text-white text-lg mb-4">This is a simple Vue 3 project starter template with Tailwind CSS</p>
            <button class="bg-white text-green-700 px-4 py-2 rounded-md">Get Started</button>

        </div>

    </section>
  
</template>