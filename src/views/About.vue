<template>
  <div class="about">
    <h1>This is an about page</h1>
    <CoolButton v-on:click="click">Click me</CoolButton>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import CoolButton from "../components/CoolButton.vue";

export default defineComponent({
  name: "About",
  components: {
    CoolButton
  },
  setup() {
    const click = () => {
      console.log(this);
    };
    return { click };
  }
});
</script>
