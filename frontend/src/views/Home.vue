<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Counter msg="boop a doo" />
    <Counter msg="boop a doo" />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Counter from "@/components/Counter.vue"; // @ is an alias to /src

export default Vue.extend({
  name: "Home",
  components: {
    Counter,
  },
});
</script>
