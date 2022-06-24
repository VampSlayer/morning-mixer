<template>
  <div class="container-fluid">
    <Categories />
    <hr />
    <Morning date="Friday 24 Jun" />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import Categories from "./components/Categories.vue";
import Morning from "./components/Morning.vue";

@Options({
  components: {
    Categories,
    Morning,
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
