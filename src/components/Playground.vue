<script setup>
import { ref } from 'vue';
const dateValue = ref('');
</script>

<template>
  <vue-tailwind-datepicker i18n="fr" v-model="dateValue" />
</template>
