<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <BlockQuote quote="Hello to the world of Vue JS" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import BlockQuote from '@/components/BlockQuote.vue';

export default {
  name: 'home',
  components: {
    HelloWorld,
    BlockQuote
  }
}
</script>
