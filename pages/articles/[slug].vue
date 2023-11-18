<script setup>
definePageMeta({
 layout: 'bos'
})
const route = useRoute();
console.log(route.params.slug)
</script>

<template>
{{ $route.params.slug }}
</template>

<style scoped>

</style>