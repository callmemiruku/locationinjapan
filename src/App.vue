<script setup>
// import HelloWorld from './components/HelloWorld.vue'
import Nev from './components/Nev.vue'
import Card from './components/Card.vue'
import Footer from './components/Footer.vue'
import items from './detail.json'
</script>

<template>
  <header>
    <Nev />
    <h1>12 สถานที่ท่องเที่ยวในประเทศญี่ปุ่น</h1>
    <Card v-bind="items[0]"/>
    <Card v-bind="items[1]"/>
    <Card v-bind="items[2]"/>
    <Card v-bind="items[3]"/>
    <Card v-bind="items[4]"/>
    <Card v-bind="items[5]"/>
    <Card v-bind="items[6]"/>
    <Card v-bind="items[7]"/>
    <Card v-bind="items[8]"/>
    <Card v-bind="items[9]"/>
    <Card v-bind="items[10]"/>
    <Card v-bind="items[11]"/>
    <Footer />

    <!--<img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div> --->
  </header>

  <main>
    <!--<TheWelcome />-->
  </main>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Kanit&display=swap');
*{
    box-sizing: border-box;
    font-family: 'Kanit', sans-serif;
    background-color: rgb(255, 254, 239);
}
h1 {
  padding-top: 30px;
  padding-bottom: 30px;
  text-align: center;
}

.grid-container {
  display: grid;
  grid-column-gap: 0.5rem;
  grid-row-gap: 0.5rem;
}
@media (min-width: 576px) {
  .grid-container { grid-template-columns: repeat(1, 1fr); }
}
@media (min-width: 992px) {
  .grid-container { grid-template-columns: repeat(3, 1fr); }
}

/*header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}*/
</style>