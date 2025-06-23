
<template>
  <div id="app">
    <h1>Pindle</h1>
    <p>Welcome to the Pi-powered e-commerce platform.</p>
    <button @click="createStore">Create Store</button>
  </div>
</template>

<script>
export default {
  name: "App",
  methods: {
    createStore() {
      alert("Store creation coming soon!");
    }
  }
};
</script>

<style>
#app {
  text-align: center;
  margin-top: 50px;
}
</style>
