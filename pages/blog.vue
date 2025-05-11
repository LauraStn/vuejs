<template>
  <h1>blog</h1>
  <button @click="increment">button</button>
  <button @click="decrement">decrement</button>
  <button @click="show">show</button>
  <!-- <input v-bind:type="text" name="" id="" v-bind:value="str" /> -->
  <input type="text" name="" id="" v-model="str" />
  {{ str }} 
  <div v-if="display">if</div>
  <p>count: {{ count }}</p>
  <ul>
    <li v-for="value in array">{{ value }}</li>
  </ul>
  <Btn type="button" label=" cgngcncgvn" value="laura" />
</template>

<script lang="ts" setup>
import Btn from '../components/Btn.vue';
const count = ref(0);
const display = ref(false);
const str = ref('super');

const show = () => {
  display.value = !display.value;
};
const increment = () => {
  count.value++;
};
const decrement = () => {
  if (count.value === 0) {
    count.value = 0;
  } else {
    count.value--;
  }
};

const array = ['un', 'dos', 'tres', 'quatro'];
</script>

<style scoped>

h1 {
  color: blue;
}
</style>
