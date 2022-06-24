<template>
  <Category title="Fitness" />
  <Category title="Learning" />
  <Category title="Rest and Relaxation" />
</template>

<script lang="ts">
import Category from "./Category.vue";
import { Options, Vue } from "vue-class-component";

@Options({
  components: {
    Category,
  },
})
export default class Categories extends Vue {}
</script>

<style scoped lang="scss"></style>
