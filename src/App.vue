<template>
  <div>
    <MenuBar />
    <router-view id="app" />
  </div>
</template>

<script>
import { defineComponent } from "vue";
import MenuBar from "./components/MenuBar.vue";

export default defineComponent({
  name: "App",
  components: {
    MenuBar,
  },
  setup() {},
});
</script>
