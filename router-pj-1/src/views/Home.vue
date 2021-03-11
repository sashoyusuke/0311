<template>
  <div class="home">
    <h2>Home</h2>
    <button @click="transition()">遷移</button>
  </div>
</template>

<script>
export default {
  methods: {
    transition() {
      this.$router.push({ name: "Detail", params: { id: 12 } });
    }
  }
};
</script>