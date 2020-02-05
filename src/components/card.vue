<template>
  <div v-bind:class="appearence" class="card text-white mb-3" style="max-width: 18rem;">
    <div class="card-header">{{header}}</div>
    <div class="card-body">
      <h5 class="card-title">{{title}}</h5>
      <p class="card-text">{{content}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    header: String,
    title: String,
    content: String,
    isActive: Boolean
  },
  computed: {
    appearence: function() {
      return this.isActive ? "bg-success" : "bg-danger"
    }
  }
};
</script>

<style scoped>
</style>
