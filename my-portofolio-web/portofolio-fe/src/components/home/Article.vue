<template>
    <section id="article" class="bg-white">
        <div class="px-10 py-8 text-start space-y-4 lg:pt-20 lg:px-32">
            <h1 class="text-primary font-bold text-2xl lg:text-3xl">My Recent Article</h1>
            <p class="text-primary text-lg font-base">Stay Informed!</p>
        </div>
        <div class="px-10 pb-8 text-left lg:pt-6 lg:px-32">
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
                        enabled: true,
                        centeredSlides: true,
                        direction: 'horizontal',
                    },
                }"
                :modules="modules"
                class="mySwiper"
            >
                <swiper-slide>
                    <Card class="drop-shadow-lg">
                        <img src="/img/education-logo.svg" alt="education logo" class="max-h-40 w-screen pb-4">
                        <p class="text-base text-end">January 2024</p>
                        <h5 class="text-primary text-xl font-bold leading-tight mb-5">POLBAN Final Project Deadline Has Been
                            Extended</h5>
                        <p class="mb-4 text-base truncate">
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi amet harum enim, iusto recusandae
                            repudiandae delectus ad exercitationem corporis. Blanditiis dolore accusamus modi magnam veniam
                            officia sint mollitia? Sequi, voluptatum.
                        </p>
                    </Card>
                </swiper-slide>
                <swiper-slide>
                    <Card class="drop-shadow-lg">
                        <img src="/img/education-logo.svg" alt="education logo" class="max-h-40 w-screen pb-4">
                        <p class="text-base text-end">January 2024</p>
                        <h5 class="text-primary text-xl font-bold leading-tight mb-5">POLBAN Final Project Deadline Has Been
                            Extended</h5>
                        <p class="mb-4 text-base truncate">
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi amet harum enim, iusto recusandae
                            repudiandae delectus ad exercitationem corporis. Blanditiis dolore accusamus modi magnam veniam
                            officia sint mollitia? Sequi, voluptatum.
                        </p>
                    </Card>
                </swiper-slide>
            </swiper>
            <div class="flex flex-col pb-8 md:hidden">
                <a href="#" class="p-3 font-bold text-center bg-primary text-light rounded-lg uppercase">
                    Show More Article
                    <i class="fa-solid fa-chevron-down"></i></a>
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