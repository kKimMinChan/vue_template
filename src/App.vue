<template>
  <h1>{{ message }}</h1>
  <HelloWorld />
</template>

<script>
import HelloWorld from "~/components/HelloWorld.vue";
export default {
  components: {
    HelloWorld,
  },
  setup() {
    return {
      message: "Hello Vue!!!",
    };
  },
};
</script>
