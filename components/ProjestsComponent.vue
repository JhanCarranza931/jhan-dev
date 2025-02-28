<script setup>

const PortfolioPersonal = {
    title:'Personal Portfolio',
    paragraph:'A personal portfolio website to showcase my projects and skills.'
}
</script>

<template>
    <section class="flex flex-col gap-9">
        <h3 class="subtitle ">Projects</h3>
        <div class="flex gap-3 flex-wrap justify-center ">
            <CardProjects :="PortfolioPersonal"/>
            <CardProjects :="PortfolioPersonal"/>
        </div>
    </section>
</template>