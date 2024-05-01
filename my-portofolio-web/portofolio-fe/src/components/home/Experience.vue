<template>
    <section id="experience" class="bg-light lg:py-8">
        <div class="px-10 py-8 text-center space-y-4">
            <h1 class="text-primary font-bold text-2xl lg:text-3xl">My Experience and Job History</h1>
            <p class="text-primary text-base md:text-lg lg:text-xl">Job History</p>
        </div>
        <div
            class="flex flex-col px-6 pb-8 space-y-4 md:flex-row md:flex-wrap md:space-x-4 md:space-y-0 md:justify-center">
            <Card>
                <h5 class="mb-2 text-xl font-bold leading-tight">PT Lapi Divusi</h5>
                <p class="text-base">Web Developer</p>
                <p class="font-light text-sm">November 2022 - July 2023</p>
                <p class="mb-4 text-base truncate">
                    Have been working part-time and involved in the development of employee data management web
                    applications. Working using Laravel framework, Bootstrap, PostgreSQL database, GitLab version
                    control, and other supporting tools. other supporting tools.
                </p>
            </Card>
            <Card>
                <h5 class="mb-2 text-xl font-bold leading-tight">PT Lapi Divusi</h5>
                <p class="text-base">Web Developer</p>
                <p class="font-light text-sm">November 2022 - July 2023</p>
                <p class="mb-4 text-base truncate">
                    Involved in the development of employee data management web applications, such as the creation of
                    features based on CRUD based features with Laravel and PostgreSQL technology.
                </p>
            </Card>
        </div>
        <div class="px-10 pb-8 text-center space-y-4">
            <p class="text-primary text-base md:text-lg lg:text-xl">Project</p>
        </div>
        <div
            class="flex flex-col px-6 pb-8 space-y-4 md:flex-row md:flex-wrap md:space-x-4 md:space-y-0 md:justify-center">
            <Card>
                <h5 class="mb-2 text-xl font-bold leading-tight">HRIS</h5>
                <p class="text-base">Project of PT Lapi Divusi</p>
                <p class="font-light text-sm">November 2022 - July 2023</p>
                <p class="mb-4 text-base truncate">
                    Involved in the development of employee data management web applications, such as the
                    creation of
                    features based on CRUD based features with Laravel and PostgreSQL technology.
                </p>
            </Card>
            <Card>
                <h5 class="mb-2 text-xl font-bold leading-tight">SI RUKUN</h5>
                <p class="text-base">Final Project on Politeknik Negeri Bandung</p>
                <p class="font-light text-sm">Maret 2023 - Desember 2024</p>
                <p class="mb-4 text-base truncate">
                    Completed the development of cover letter and certificate management features, population
                    data
                    collection features, and user management features using Laravel, PHP, PostgreSQL, and
                    Bootstrap
                    development technologies.
                </p>
            </Card>
            <a href="#" class="p-3 font-semibold text-center bg-primary text-light rounded-lg uppercase md:hidden">Show
                More
                Project <i class="fa-solid fa-chevron-down"></i></a>
        </div>
    </section>
</template>

<script>
import Card from '../Card.vue';

export default {
    components: {
        Card,
    },
};
</script>

<style lang="scss" scoped></style>