<template>
  <button type="button">{{ props.label }}</button>
</template>

<script lang="ts" setup>
const props = defineProps<{label: string}>();
</script>
<style></style>
