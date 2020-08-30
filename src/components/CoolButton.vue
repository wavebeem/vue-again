<template>
  <button>
    <slot></slot>
  </button>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "CoolButton"
});
</script>

<style scoped>
button {
  background: red;
  color: white;
}
</style>
