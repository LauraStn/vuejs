<template></template>
<script lang="ts" setup>
const {status, data: todo} = await useLazyFetch(
  'https://jsonplaceholder.typicode.com/todos'
);
watch(todo, (newTodo) => {
  console.log('status:', status, 'todo:', todo);
});
</script>
