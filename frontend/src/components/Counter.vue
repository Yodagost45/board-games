<template>
  <div>
    <p>The count is: {{ count }}</p>
    <b-button variant="success" @click="addCount()">Click Me!</b-button>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "HelloWorld",
  props: {
    msg: String,
  },
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    addCount() {
      this.count += 1;
    },
  },
});
</script>
