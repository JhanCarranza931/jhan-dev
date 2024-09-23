<script setup>

const user = {
    name:'Jhan',
    man:'Carranza'
}
</script>

<template>
    <section class="flex flex-col gap-9">
        <h3 class="subtitle ">Projects</h3>
        <div class="flex gap-3 flex-wrap justify-center ">
            <CardProjects :="user"/>
            <CardProjects :="user"/>
            <CardProjects :="user"/>
            <CardProjects :="user"/>
        </div>
    </section>
</template>