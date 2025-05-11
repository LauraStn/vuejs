<template>
  <main>
    <BarberHeader />
    <Card />
    <div class="home">
      <h1>your style starts here</h1>
      <h2>
        We build our passion for the art of barbering through our commitment to
        our customers.
      </h2>
      <button>book an appointment</button>
    </div>
  </main>
</template>
<script lang="ts" setup>
import BarberHeader from '~/components/BarberHeader.vue';
// import Card from '../../components/Card.vue';
const x = ref(false);
provide('value', 20)
const route = useRoute();
if (route.name === 'barber') {
  console.log(x.value);
}
</script>
<style>
/* body {
  background-color: brown;
} */
.home {
  background-image: url('../../assets/img/barber-home.jpg');
  height: 600px;
  display: flex;
  flex-direction: column;
}
</style>
