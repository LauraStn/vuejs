<template>
  <h1><Btn :label="label1" /></h1>
  <Btn :class="btn" label="my button" @click="console.log()" />
  <input type="text" v-model="cls" />
  {{ cls }}
</template>

<script lang="ts" setup>
import {ref} from 'vue';
import Btn from '~/components/Btn.vue';

const btn = 'text-red';
const product = {
  categoryId: 23,
  name: 'mon produit',
};

const label = ref('Clique par la');
const label1 = ref('Clique par ici');
const cls = ref('text-red');

watch(
  () => cls.value,
  (newValue) => {
    if (newValue) console.log('Ca a changé');
  }
);
</script>
