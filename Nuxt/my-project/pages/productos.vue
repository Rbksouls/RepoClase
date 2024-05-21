<template>
    <slot/>
    <div>
        <h1>Esta es la pagina de productos</h1>
    </div>
    <NuxtLink to="/">Inicio</NuxtLink>
</template>

<script setup>
definePageMeta({
 layout:"menu"
})
</script>