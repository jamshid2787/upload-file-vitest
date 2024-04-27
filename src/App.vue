<script setup lang="ts">
import Single from './components/singleUpload.vue';
import Multiple from './components/multipleUpload.vue';
</script>

<template>
	<Single :maxSize="10 * 1024 * 1024" fileType="application/pdf" />
	<Multiple :maxSize="10 * 1024 * 1024" :maxElementCount="5" :isMultiple="true" />
</template>

<style scoped></style>
