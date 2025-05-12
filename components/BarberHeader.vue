<template>
  <header>
    <div><link rel="stylesheet" href="/" />Barber</div>
    <div>
      <nav>
        <ul>
          <li>home</li>
          <li>about us</li>
          <li>pages</li>
          <li>contact</li>
        </ul>
      </nav>
    </div>
    <Btn />
    <div></div>
  </header>
</template>
<script setup>
import Btn from './Btn.vue';
</script>
<style scoped>
header {
  display: flex;
  justify-content: space-between;
  background-color: black;
  color: white;
}
</style>
