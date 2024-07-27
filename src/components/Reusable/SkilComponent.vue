<script setup>
const props=defineProps(['header'])
</script>
<template>
    <div class="sm:px-5 lg:px-3">
        <h2 class="text-gray-900 text-[25px]">{{props.header }}</h2>
    </div>
</template>