<template>
    <section id="about-me" class="bg-sky-100 lg:px-24">
        <div class="px-10 py-8 space-y-4">
            <h1 class="text-primary font-bold text-2xl">About Me</h1>
            <p class="truncate" ref="show">Fresh graduate as a software engineer with experience in the field of
                computer engineering and informatics especially web development as a backend and frontend developer.
                Innovative and creative in in dealing with problems.</p>
            <button @click="showMore" class="text-secondary">Show more <i class="fa-solid fa-arrow-right"></i></button>
        </div>
    </section>
</template>

<script setup>
import { ref } from "vue";

const show = ref(null);

function showMore() {
    const showClass = show.value.classList;
    if (showClass == "truncate") {
        showClass.remove("truncate");
    } else {
        showClass.add("truncate");
    }
}


</script>

<style lang="scss" scoped></style>