<template>
    <section id="skills" class="bg-primary lg:py-8">
        <div class="px-10 py-8 text-end space-y-4">
            <h1 class="text-light font-bold text-2xl lg:text-3xl">Technology That I Usually Use</h1>
        </div>
        <div class="flex flex-col px-6 pb-8 space-y-4 md:items-center text-center lg:px-0 lg:flex-row lg:flex-wrap lg:space-x-4 lg:space-y-0 lg:justify-center">
            <Card class="lg:max-w-xs">
                <i class="fa-brands fa-laravel text-7xl"></i>
                <h5 class="text-primary text-xl font-bold leading-tight mb-5">Laravel</h5>
                <p class="mb-4 text-base truncate">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque, modi aliquam nemo culpa soluta
                    amet. Libero esse commodi ab labore sint necessitatibus nobis blanditiis. Id at vero similique eaque
                    architecto.
                </p>
            </Card>
            <Card class="lg:max-w-xs">
                <i class="fa-brands fa-php text-7xl"></i>
                <h5 class="text-primary text-xl font-bold leading-tight mb-5">PHP</h5>
                <p class="mb-4 text-base truncate">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque, modi aliquam nemo culpa soluta
                    amet. Libero esse commodi ab labore sint necessitatibus nobis blanditiis. Id at vero similique eaque
                    architecto.
                </p>
            </Card>
            <Card class="lg:max-w-xs">
                <i class="fa-brands fa-node-js text-7xl"></i>
                <h5 class="text-primary text-xl font-bold leading-tight mb-5">Node.js</h5>
                <p class="mb-4 text-base truncate">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque, modi aliquam nemo culpa soluta
                    amet. Libero esse commodi ab labore sint necessitatibus nobis blanditiis. Id at vero similique eaque
                    architecto.
                </p>
            </Card>
            <div class="flex flex-col pb-8 lg:hidden">
                <a href="#" class="p-3 font-bold text-center bg-secondary text-light rounded-lg uppercase">Show
                    More Technology
                    <i class="fa-solid fa-chevron-down"></i></a>
            </div>
        </div>
    </section>
</template>

<script>
import Card from "../Card.vue";

export default {
    components: {
        Card,
    },
};
</script>

<style lang="scss" scoped></style>