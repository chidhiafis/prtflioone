<script setup>
const props=defineProps(['heading','description'])

</script>
<template>
    <div class="flex flex-col px-3 py-3">
        <h3 class="text-gray-900 text-[27px] mb-4">{{ props.heading }}</h3>
        <p class="text-gray-600 text-[22px]">{{ props.description }}</p>
    </div>
</template>