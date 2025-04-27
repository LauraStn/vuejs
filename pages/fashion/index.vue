<template>
  <main>
    <div class="first">
      <img src="../../assets/img/living.jpg" alt="" />
      <h2>best places to be a fashion runway model</h2>
    </div>
    <div class="second">
      <h1>Fashion</h1>
      <h2>fashion & design academy</h2>
      <p>
        Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi
        ut aliquip ex ea commodo consequat. Duis aute irure dolor in
        reprehenderit in voluptate velit esse cillum
      </p>
      <ul>
        <li>miami</li>
        <li>hawaii</li>
        <li>chicago</li>
        <li>new york</li>
      </ul>
    </div>
    <div class="third">
      <img src="../../assets/img/home.jpg" alt="" />
    </div>
  </main>
</template>
<script lang="ts" setup></script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Merriweather:opsz,wdth,wght@18..144,87.5,700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
main {
  display: flex;
  margin-top: 150px;
  margin-left: 350px;
  margin-right: 350px;
  gap: 60px;
}
img {
  border-radius: 50%;
  width: 350px;
}
div {
  display: flex;
  height: 200px;
  flex-direction: column;
}
h1 {
  font-family: 'Merriweather' serif;
  font-size: 3.75rem;
  margin: 0;
}
h2 {
  font-family: 'Roboto', sans-serif;
  text-transform: uppercase;
  font-weight: 100;
  letter-spacing: 1px;
  font-size: 1.25rem;
  margin: 0;
}
p {
  font-family: 'Open sans', sans-serif;
  line-height: 1.6;
  font-size: 1rem;
  font-weight: 600;
}
.first {
  display: flex;
  align-items: center;
  gap: 30px;
}
.second {
  margin-top: 130px;
  width: 300px;
}
.third {
  margin-top: 250px;
}
.first h2 {
  width: 270px;
}
ul {
  font-family: 'Open sans', sans-serif;
  text-transform: uppercase;
  letter-spacing: 2px;
  line-height: 1.6;
  font-weight: 300;
}
</style>
