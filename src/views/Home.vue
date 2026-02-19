<template>
  <div class="home">
    <h1>Welcome to Fools Tools</h1>
    <p>A fool's tool website for fools by a fool.</p>
    <HelloWorld msg="Get started by exploring the tools!" />
  </div>
</template>

<script>
import HelloWorld from '../components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
.home {
  padding: 2rem;
}
</style>
