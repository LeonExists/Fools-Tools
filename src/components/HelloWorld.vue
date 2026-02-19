<template>
  <div class="card">
    <h2>{{ msg }}</h2>
    <p>
      Start building your tools here!
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: {
      type: String,
      required: true
    }
  }
}
</script>

<style scoped>
.card {
  padding: 2rem;
  background-color: #f9f9f9;
  border-radius: 8px;
  margin: 2rem auto;
}

@media (prefers-color-scheme: dark) {
  .card {
    background-color: #1a1a1a;
  }
}

h2 {
  color: #42b983;
}
</style>
