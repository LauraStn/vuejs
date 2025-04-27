<template>
  <button :type="props.type">{{ props.label }}</button>
  <input type="text" name="" id="" :value="props.value" />
</template>
<script lang="ts" setup>
import {defineProps} from 'vue';
const props = defineProps<{type: 'button'; label: string; value: string}>();
</script>
<style></style>
