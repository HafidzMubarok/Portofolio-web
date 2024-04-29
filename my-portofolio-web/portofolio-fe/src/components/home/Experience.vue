<template>
    <section id="experience" class="bg-light lg:py-8">
        <div class="px-10 py-8 text-center space-y-4">
            <h1 class="text-primary font-bold text-2xl lg:text-3xl">My Experience and Job History</h1>
            <p class="text-primary text-base md:text-lg lg:text-xl">Job History</p>
        </div>
        <div
            class="flex flex-col px-6 pb-8 space-y-4 md:flex-row md:flex-wrap md:space-x-4 md:space-y-0 md:justify-center">
            <div
                class="block rounded-lg bg-white p-12 text-surface shadow-secondary-1 text-primary space-y-4 md:max-w-xs lg:max-w-md">
                <h5 class="mb-2 text-xl font-bold leading-tight">PT Lapi Divusi</h5>
                <p class="text-base">Web Developer</p>
                <p class="font-light text-sm">November 2022 - July 2023</p>
                <p class="mb-4 text-base truncate">
                    Have been working part-time and involved in the development of employee data management web
                    applications. Working using Laravel framework, Bootstrap, PostgreSQL database, GitLab version
                    control, and other supporting tools. other supporting tools.
                </p>
                <button type="button" class="inline-block rounded bg-primary px-6 pb-2 pt-2.5 w-max text-xs font-medium uppercase leading-normal 
                    text-light shadow-primary-3 transition duration-150 ease-in-out hover:bg-primary-accent-300 hover:shadow-primary-2 
                    focus:bg-primary-accent-300 focus:shadow-primary-2 focus:outline-none focus:ring-0 active:bg-primary-600 
                    active:shadow-primary-2" data-twe-ripple-init data-twe-ripple-color="light">
                    Show More
                </button>
            </div>
            <div
                class="block rounded-lg bg-white p-12 text-surface shadow-secondary-1 text-primary space-y-4 md:max-w-xs lg:max-w-md">
                <h5 class="mb-2 text-xl font-bold leading-tight">PT Lapi Divusi</h5>
                <p class="text-base">Web Developer</p>
                <p class="font-light text-sm">November 2022 - July 2023</p>
                <p class="mb-4 text-base truncate" ref="show">
                    Involved in the development of employee data management web applications, such as the creation of
                    features based on CRUD based features with Laravel and PostgreSQL technology.
                </p>
                <button @click="showMore" type="button" class="inline-block rounded bg-primary px-6 pb-2 pt-2.5 w-max text-xs font-medium uppercase leading-normal 
                    text-light shadow-primary-3 transition duration-150 ease-in-out hover:bg-primary-accent-300 hover:shadow-primary-2 
                    focus:bg-primary-accent-300 focus:shadow-primary-2 focus:outline-none focus:ring-0 active:bg-primary-600 
                    active:shadow-primary-2" data-twe-ripple-init data-twe-ripple-color="light">
                    Show More
                </button>
            </div>
        </div>
        <div class="px-10 pb-8 text-center space-y-4">
            <p class="text-primary text-base md:text-lg lg:text-xl">Project</p>
        </div>
        <div
            class="flex flex-col px-6 pb-8 space-y-4 md:flex-row md:flex-wrap md:space-x-4 md:space-y-0 md:justify-center">
            <div
                class="block rounded-lg bg-white p-12 text-surface shadow-secondary-1 text-primary space-y-4 md:max-w-xs lg:max-w-md">
                <h5 class="mb-2 text-xl font-bold leading-tight">HRIS</h5>
                <p class="text-base">Project of PT Lapi Divusi</p>
                <p class="font-light text-sm">November 2022 - July 2023</p>
                <p class="mb-4 text-base truncate">
                    Involved in the development of employee data management web applications, such as the creation of
                    features based on CRUD based features with Laravel and PostgreSQL technology.
                </p>
                <button type="button" class="inline-block rounded bg-primary px-6 pb-2 pt-2.5 w-max text-xs font-medium uppercase leading-normal 
                    text-light shadow-primary-3 transition duration-150 ease-in-out hover:bg-primary-accent-300 hover:shadow-primary-2 
                    focus:bg-primary-accent-300 focus:shadow-primary-2 focus:outline-none focus:ring-0 active:bg-primary-600 
                    active:shadow-primary-2" data-twe-ripple-init data-twe-ripple-color="light">
                    Show More
                </button>
            </div>
            <div
                class="block rounded-lg bg-white p-12 text-surface shadow-secondary-1 text-primary space-y-4 md:max-w-xs lg:max-w-md">
                <h5 class="mb-2 text-xl font-bold leading-tight">SI RUKUN</h5>
                <p class="text-base">Final Project on Politeknik Negeri Bandung</p>
                <p class="font-light text-sm">Maret 2023 - Desember 2024</p>
                <p class="mb-4 text-base truncate">
                    Completed the development of cover letter and certificate management features, population data
                    collection features, and user management features using Laravel, PHP, PostgreSQL, and Bootstrap
                    development technologies.
                </p>
                <button type="button" class="inline-block rounded bg-primary px-6 pb-2 pt-2.5 w-max text-xs font-medium uppercase leading-normal 
                    text-light shadow-primary-3 transition duration-150 ease-in-out hover:bg-primary-accent-300 hover:shadow-primary-2 
                    focus:bg-primary-accent-300 focus:shadow-primary-2 focus:outline-none focus:ring-0 active:bg-primary-600 
                    active:shadow-primary-2" data-twe-ripple-init data-twe-ripple-color="light">
                    Show More
                </button>
            </div>
            <a href="#" class="p-3 font-semibold text-center bg-primary text-light rounded-lg uppercase md:hidden">Show
                More
                Project <i class="fa-solid fa-chevron-down"></i></a>
        </div>
    </section>
</template>

<script setup>
import { ref } from "vue";

const show = ref(null);

function showMore() {
    const showClass = show.value.classList;

    if (showClass.contains("truncate")) {
        showClass.remove("truncate");
    } else {
        showClass.add("truncate");
    }
}
</script>

<style lang="scss" scoped></style>