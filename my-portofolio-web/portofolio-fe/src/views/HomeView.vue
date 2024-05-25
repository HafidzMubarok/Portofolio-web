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
    <div class="sticky text-end bottom-16 pe-16">
        <a href="#home" class="rounded-full py-4 px-5 bg-secondary text-light text-center"><i class="fa-solid fa-arrow-up"></i></a>
    </div>
</template>
