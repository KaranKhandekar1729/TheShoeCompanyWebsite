<script setup>
import aboutUsBackground from '../assets/images/about-us-background.png'
</script>

<template>
<section id="about" class="section-container mt-32 flex flex-col md:flex-row md:space-x-12 scroll-mt-28">
    <h2 class="text-3xl my-6 text-center font-bold md:hidden">About Us!</h2>
    <div :style="`background-image:url(${aboutUsBackground})`" class="bg-no-repeat md:w-full self-center">
        <img src="../assets/images/about-shoe-company.png" alt="">
    </div>
    <div class="space-y-8 max-w-xl md:w-full">
        <h2 class="text-6xl font-bold hidden md:block">
            About Us!
        </h2>
        <p>
            For each one of those shoe sweethearts out there, THE SHOE COMPANY
            offer the one-stop goal to pick the correct match of footwear.
        </p>
        <p>
            Gone are the days when you needed to go from store to store to locate
            the correct style and size for yourself.
        </p>
        <p>
            At THE SHOE COMPANY, you can locate a vast accumulation of dashing
            footwear in all sizes and styles, all inside a couple of snaps.
        </p>
        <p>
            Simple right? Not just we are here to spare your time, we are putting
            forth you the most dazzling footwear alternatives from all the
            first-rate brands like DAVINCHI, PRINCESS, and SIGNATURE. At
            'Organization Name', we offer men, ladies, and child's shoes perfect
            for any and each event.
        </p>
    </div>
</section>
</template>
