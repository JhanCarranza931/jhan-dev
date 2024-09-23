<script setup lang="ts">
    defineProps({
        title: String,
        man: String
    })
</script>
    
<template>

    <article class="flex w-full     sm:w-[calc(50%-20px)]  flex-col gap-5 p-5  rounded-lg " style="border: 1px solid rgba(150, 150, 150, 0.10);background: rgba(26, 26, 26, 0.50);">
        <h5 class=" text-white flex items-center text-base"> <Icon name="material-symbols:folder" class="mr-3 "/>Personal Portfolio</h5>
        <p class="text-white text-sm">A personal portfolio website to showcase my projects and skills.</p>
        <ul class=" list-disc ml-6 gray">
            <li class=" text-sm">A personal portfolio website to showcase my projects and skills.</li>
            <li class=" text-sm">A personal portfolio website to showcase my projects and skills.</li>
        </ul>
    </article>

</template>