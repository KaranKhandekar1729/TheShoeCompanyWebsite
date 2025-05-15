<script setup>
import heroBackground from '../assets/images/hero-background.png'
</script>

<template>
    <section id="hero" :style="`background-image:url(${heroBackground})`" class="bg-cover md:bg-contain bg-no-repeat bg-right pt-36 section-container">
        <div class="flex flex-col md:flex-row md:items-center justify-between max-w-6xl mx-auto">
            <h1 class="text-6xl font-bold leading-[64px]">
                THE <br/>
                SHOE <br/>
                COMPANY <br/>
            </h1>
            <div>
                <img class="w-full max-w-xl" src="../assets/images/hero-image.png" alt="white shoe image">
            </div>
        </div>
    </section>
</template>