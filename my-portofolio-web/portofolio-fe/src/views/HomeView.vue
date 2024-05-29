<script setup>
    import NavBar from "../components/NavBar.vue";
    import Hero from "../components/home/Hero.vue";
    import AboutMe from "../components/home/AboutMe.vue";
    import Experience from "../components/home/Experience.vue";
    import Skills from "../components/home/Skills.vue";
    import Education from "../components/home/Education.vue";
    import Article from "../components/home/Article.vue";
    import Feedback from "../components/home/Feedback.vue";
</script>

<template>
    <NavBar />
    <Hero />
    <AboutMe />
    <Experience />
    <Skills />
    <Education />
    <Article />
    <Feedback />
    <a href="#home" class="rounded-full fixed w-fit bottom-16 right-16 py-4 px-6 bg-secondary text-light text-center z-10"><i class="fa-solid fa-arrow-up"></i></a>
</template>
