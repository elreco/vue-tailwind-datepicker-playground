<script setup>
import { ref } from 'vue';
const dateValue = ref('');
</script>

<template>
  <vue-tailwind-datepicker v-model="dateValue" />
</template>
