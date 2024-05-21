<template>
   <slot/>
    <NuxtPage></NuxtPage>
    <h1 class="text-3xl font-bold underline">
      Hello world!
    </h1>
    <NuxtLink to="/contacto">Contacto</NuxtLink>
    <br>
    <NuxtLink to="/about">Sobre mi</NuxtLink>
    <br>
    <NuxtLink to="/productos">Tienda</NuxtLink>
</template>
<script setup>
 definePageMeta({
  layout:"menu"
 })
</script>

