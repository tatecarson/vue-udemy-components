<template>
  <div>
    <app-header></app-header>
    <hr>
    <app-servers></app-servers>
    <server-details></server-details>
    <hr>
    <server-managed></server-managed>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Servers from "./components/Servers.vue";
import ServerDetails from "./components/ServerDetails.vue";
import ServerManaged from "./components/ServerManaged.vue";

export default {
  components: {
    "app-header": Header,
    "app-servers": Servers,
    "server-details": ServerDetails,
    "server-managed": ServerManaged
  }
};
</script>

