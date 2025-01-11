<script setup>
defineProps({
    title: String,
    link: String
})
</script>
<template>
    <section>
        <div class="container m-auto py-6 px-6">
            <RouterLink :to="link" class="text-green-500 hover:text-green-600 flex items-center">
                <i class="pi pi-arrow-circle-left mr-2"></i> {{ title }}
            </RouterLink>
        </div>
    </section>
</template>
