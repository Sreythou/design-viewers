<template>
  <nav class="menu-bar">Menu</nav>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "MenuBar",
  setup() {},
});
</script>

<style lang="scss" scoped>
.menu-bar {
  background-color: rgb(37, 37, 37);
  color: white;
  padding: 10px;
  top: 0;
  z-index: 50;
  position: fixed;
  width: 100%;
}
</style>
