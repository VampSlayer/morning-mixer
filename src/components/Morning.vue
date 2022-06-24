<template>
  <div>
    <h1>Good Morning</h1>
    <h2>{{ date }}</h2>
    <h3>For your morning mix let's do:</h3>
    <div class="row justify-content-md-center">
      <input class="col-1" type="checkbox" />
      <h3 class="col-1">Yoga</h3>
    </div>
    <div class="row justify-content-md-center">
      <input class="col-1" type="checkbox" />
      <h3 class="col-1">Reading</h3>
    </div>
    <div class="row justify-content-md-center">
      <input class="col-1" type="checkbox" />
      <h3 class="col-1">Meditation</h3>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    date: String,
  },
})
export default class Morning extends Vue {
  msg!: string;
}
</script>

<style scoped lang="scss"></style>
