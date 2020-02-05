<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <div class="col">
          <Card header="Key" title="Used" content="Description" isActive></Card>
          <Card header="Key" title="Used" content="Description"></Card>
          <Card header="Key" title="Used" content="Description"></Card>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Card from "./components/card.vue";

export default {
  name: "app",
  components: {
    Card
  }
};
</script>

<style>
</style>
