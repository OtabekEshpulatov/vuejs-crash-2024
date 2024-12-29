<script setup>
import { RouterLink } from 'vue-router';

defineProps({
    href: {
        type: String,
        default: "#"
    },
    text: {
        type: String,
        default: "Back"
    }
})
</script>

<template>
    <!-- Go Back -->
    <section>
        <div class="container m-auto py-6 px-6">
            <RouterLink :to="`${href}`" class="text-green-500 hover:text-green-600 flex items-center">
                <i class="pi pi-arrow-circle-left mr-2"></i> {{ text }}
            </RouterLink>
        </div>
    </section>
</template>