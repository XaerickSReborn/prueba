<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import Button from 'primevue/button';
import InputText from 'primevue/inputtext';
import { ref } from 'vue';

const text = ref('');
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="Hola" />
    </div>
    <br>
    
  </header>
  <section>
    <InputText v-model="text" placeholder="Enter your name" />
    <Button label="Click" />
  </section>
  <main>
    <!-- <TheWelcome />  -->
  </main>
</template>

<style scoped>

</style>
