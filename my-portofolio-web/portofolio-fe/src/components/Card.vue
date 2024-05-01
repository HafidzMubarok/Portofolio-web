<template>
    <div
        class="block rounded-lg bg-white p-12 text-surface shadow-secondary-1 text-primary space-y-4 md:max-w-xs lg:max-w-md">
        <slot></slot>
        <button type="button" class="inline-block rounded bg-primary px-6 pb-2 pt-2.5 w-max text-xs font-medium uppercase leading-normal 
                text-light shadow-primary-3 transition duration-150 ease-in-out hover:bg-primary-accent-300 hover:shadow-primary-2 
                focus:bg-primary-accent-300 focus:shadow-primary-2 focus:outline-none focus:ring-0 active:bg-primary-600 
                active:shadow-primary-2" data-twe-ripple-init data-twe-ripple-color="light">
            Show More
        </button>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped></style>