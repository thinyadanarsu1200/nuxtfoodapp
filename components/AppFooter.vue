<template>
  <footer>
    copyright&copy; <span>{{ year }}</span>
  </footer>
</template>

<script>
import { reactive, toRefs } from "vue";

export default {
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>

<style lang="scss" scoped></style>
