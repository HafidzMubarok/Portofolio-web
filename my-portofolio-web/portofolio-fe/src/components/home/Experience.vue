<template>
    <section id="history" class="bg-light lg:py-8">
        <div class="px-10 py-8 text-center space-y-4">
            <h1 class="text-primary font-bold text-2xl lg:text-3xl">My Experience and Job History</h1>
            <p class="text-primary text-base md:text-lg lg:text-xl">Job History</p>
        </div>
        <div
            class="flex flex-col px-6 pb-8 space-y-4 md:flex-row md:space-x-4 md:space-y-0 md:justify-center">
            <Card data-collapse-target="detail-history-card-1" controls="detail-history-card-1" btn-text="Show Detail">
                <h5 class="mb-2 text-xl font-bold leading-tight">PT Lapi Divusi</h5>
                <p class="text-base">Web Developer</p>
                <p class="font-light text-sm">November 2022 - July 2023</p>
                <p class="mb-4 text-base hidden" id="detail-history-card-1">
                    Have been working part-time and involved in the development of employee data management web
                    applications. Working using Laravel framework, Bootstrap, PostgreSQL database, GitLab version
                    control, and other supporting tools. other supporting tools.
                </p>
            </Card>
            <Card data-collapse-target="detail-history-card-2" controls="detail-history-card-2" btn-text="Show Detail">
                <h5 class="mb-2 text-xl font-bold leading-tight">PT Lapi Divusi</h5>
                <p class="text-base">Web Developer</p>
                <p class="font-light text-sm">November 2022 - July 2023</p>
                <p class="mb-4 text-base hidden" id="detail-history-card-2">
                    Involved in the development of employee data management web applications, such as the creation of
                    features based on CRUD based features with Laravel and PostgreSQL technology.
                </p>
            </Card>
        </div>
        <div class="px-10 pb-8 text-center space-y-4">
            <p class="text-primary text-base md:text-lg lg:text-xl">Project</p>
        </div>
        <div class="px-6 md:px-24 lg:px-12">
            <swiper
                :enabled="false"
                :direction="'vertical'"
                :slides-per-view="'auto'"
                :space-between="16"
                :pagination="{
                    clickable: true,
                }"
                :navigation="true"
                :breakpoints="{
                    '768': {
                        slidesPerView: 'auto',
                        spaceBetween: 10,
                        enabled: true,
                        centeredSlides: true,
                        direction: 'horizontal',
                    },
                    '976': {
                        slidesPerView: 'auto',
                        spaceBetween: 20,
                        enabled: true,
                        centeredSlides: true,
                        direction: 'horizontal',
                    },
                }"
                :modules="modules"
                class="mySwiper"
                >
                <swiper-slide>
                    <Card data-collapse-target="detail-project-card-1" controls="detail-project-card-1" btn-text="Show Detail">
                        <h5 class="mb-2 text-xl font-bold leading-tight">HRIS</h5>
                        <p class="text-base">Project of PT Lapi Divusi</p>
                        <p class="font-light text-sm">November 2022 - July 2023</p>
                        <p class="mb-4 text-base hidden" id="detail-project-card-1">
                            Involved in the development of employee data management web applications, such as the
                            creation of
                            features based on CRUD based features with Laravel and PostgreSQL technology.
                        </p>
                    </Card>
                </swiper-slide>
                <swiper-slide>
                    <Card data-collapse-target="detail-project-card-2" controls="detail-project-card-2" btn-text="Show Detail">
                        <h5 class="mb-2 text-xl font-bold leading-tight">SI RUKUN</h5>
                        <p class="text-base">Final Project on Politeknik Negeri Bandung</p>
                        <p class="font-light text-sm">Maret 2023 - Desember 2024</p>
                        <p class="mb-4 text-base hidden" id="detail-project-card-2">
                            Completed the development of cover letter and certificate management features, population
                            data
                            collection features, and user management features using Laravel, PHP, PostgreSQL, and
                            Bootstrap
                            development technologies.
                        </p>
                    </Card>
                </swiper-slide>
                <swiper-slide>
                    <Card data-collapse-target="detail-project-card-3" controls="detail-project-card-3" btn-text="Show Detail">
                        <h5 class="mb-2 text-xl font-bold leading-tight">SI RUKUN</h5>
                        <p class="text-base">Final Project on Politeknik Negeri Bandung</p>
                        <p class="font-light text-sm">Maret 2023 - Desember 2024</p>
                        <p class="mb-4 text-base hidden" id="detail-project-card-3">
                            Completed the development of cover letter and certificate management features, population
                            data
                            collection features, and user management features using Laravel, PHP, PostgreSQL, and
                            Bootstrap
                            development technologies.
                        </p>
                    </Card>
                </swiper-slide>
            </swiper>
            <div
                class="flex flex-col pb-8 md:hidden">
                <a href="#" class="p-3 font-semibold text-center bg-primary text-light rounded-lg uppercase">Show
                    More
                    Project <i class="fa-solid fa-chevron-down"></i></a>
            </div>
        </div>
    </section>
</template>

<script>
import Card from '../Card.vue';
import { Swiper, SwiperSlide } from 'swiper/vue';
import { Navigation, Pagination } from 'swiper/modules';

import 'swiper/css';

import 'swiper/css/pagination';
import 'swiper/css/navigation';

export default {
    components: {
        Card,
        Swiper,
        SwiperSlide,
    },
    setup() {
      return {
        modules: [Pagination, Navigation],
      };
    },
};
</script>

<style lang="scss" scoped></style>