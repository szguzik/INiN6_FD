<script setup>
const showText = ref(false);
const textButton = ref('show text');

const toggleText = () => {
    showText.value = !showText.value;
    textButton.value = showText.value ? 'hide text' : 'show text';
}

</script>
<template>
    <h1>Strona główna</h1>
    <button @click="toggleText">{{ textButton }}</button>
    <h2 v-if="showText">Pojawile sie!</h2>
</template>
<style scoped>

</style>