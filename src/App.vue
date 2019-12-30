/* eslint-disable vue/valid-v-for */
<template>
  <div id="app">
    <app-servers v-for="server in 5" :key="server"></app-servers>
  </div>
</template>

<script>
import ServerStatus from "./components/ServerStatus.vue";
export default {
  name: "app",
  components: {
    "app-servers": ServerStatus
  }
};
</script>
