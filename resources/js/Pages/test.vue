<script setup>

defineProps({
    name: String,
})

</script>

<template>
    <div class="hero min-h-screen bg-base-200">
        <div class="hero-content text-center">
            <div class="max-w-md">
                <h5 class="text-2xl font-bold animate-bounce">Made with ❤ by {{ name }}!</h5>
            </div>
        </div>
    </div>
</template>

