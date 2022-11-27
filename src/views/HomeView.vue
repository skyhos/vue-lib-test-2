<template>
  <div class="home">
    <HelloWorld msg="Test!!!" />
    <img alt="Vue logo" src="../assets/logo.png" />
    <ByeWorld msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import ByeWorld from "@/components/ByeWorld.vue"; // @ is an alias to /src
import { HelloWorld } from "vue-lib-test-1";

export default defineComponent({
  name: "HomeView",
  components: {
    HelloWorld,
    ByeWorld,
  },
});
</script>
