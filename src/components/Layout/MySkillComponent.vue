<script setup>
import SkilComponent from '../Reusable/SkilComponent.vue';

</script>
<template>
    <div class="mt-4 flex flex-col">
        <h1 class="text-[34px] text-gray-900 text-center mb-4">My Skill </h1>
        <div class="grid md:grid-cols-4 sm:grid-cols-1" >
            <SkilComponent header="html"></SkilComponent>
            <SkilComponent header="javascript"></SkilComponent>
            <SkilComponent header="python"></SkilComponent>
            <SkilComponent header="tailwind"></SkilComponent>
        </div>
    </div>
</template>