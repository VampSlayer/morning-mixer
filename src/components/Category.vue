<template>
  <div>
    <h1>{{ title }}</h1>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    title: String,
  },
})
export default class Category extends Vue {
  msg!: string;
}
</script>

<style scoped lang="scss"></style>
