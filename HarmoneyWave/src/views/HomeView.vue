<script setup>
import HomeCard from '../components/HomeCard.vue';
</script>

<template>
    <!-- begin of row 1 -->
<div class="p-8">
    <button
        type="button"
        class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
        Podcasts to make you smarter
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
        <HomeCard image="https://picsum.photos/id/30/300/300" title="Title is here" subTitle="Subtitle is here"/>
        <HomeCard image="https://picsum.photos/id/45/300/300" title="Title is here" subTitle="Subtitle is here"/>
        <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Title is here" subTitle="Subtitle is here"/>
        <HomeCard class="lg:block hidden" image="https://picsum.photos/id/67/300/300" title="Title is here" subTitle="Subtitle is here"/>
        <HomeCard class="xl:block hidden" image="https://picsum.photos/id/100/300/300" title="Title is here" subTitle="Subtitle is here"/>
    </div>
</div>
<!-- end of row 1 -->

    <!-- begin of row 2 -->
    <div class="p-8">
    <button
        type="button"
        class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
        recommended for radio
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
        <HomeCard image="https://picsum.photos/id/28/300/300" title="Title is here" subTitle="Subtitle is here"/>
        <HomeCard image="https://picsum.photos/id/10/300/300" title="Title is here" subTitle="Subtitle is here"/>
        <HomeCard class="md:block hidden" image="https://picsum.photos/id/85/300/300" title="Title is here" subTitle="Subtitle is here"/>
        <HomeCard class="lg:block hidden" image="https://picsum.photos/id/19/300/300" title="Title is here" subTitle="Subtitle is here"/>
        <HomeCard class="xl:block hidden" image="https://picsum.photos/id/99/300/300" title="Title is here" subTitle="Subtitle is here"/>
    </div>
</div>
<!-- end of row 2 -->

    <!-- begin of row 3 -->
    <div class="p-8">
    <button
        type="button"
        class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
        recommended for you
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
        <HomeCard image="https://picsum.photos/id/69/300/300" title="Title is here" subTitle="Subtitle is here"/>
        <HomeCard image="https://picsum.photos/id/88/300/300" title="Title is here" subTitle="Subtitle is here"/>
        <HomeCard class="md:block hidden" image="https://picsum.photos/id/2/300/300" title="Title is here" subTitle="Subtitle is here"/>
        <HomeCard class="lg:block hidden" image="https://picsum.photos/id/39/300/300" title="Title is here" subTitle="Subtitle is here"/>
        <HomeCard class="xl:block hidden" image="https://picsum.photos/id/70/300/300" title="Title is here" subTitle="Subtitle is here"/>
    </div>
</div>
<!-- end of row 3 -->
</template>
