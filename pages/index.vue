<script setup>

const localePath = useLocalePath()

</script>

<template>
    <div>
        <NuxtLink :to="localePath({path: '/about', query: {query: 'query'}})">link</NuxtLink>
    </div>
</template>