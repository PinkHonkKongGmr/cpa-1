<template>
  <div id="app">
    <Marketing />
  </div>
</template>

<script>
import Marketing from "./components/marketing.vue";

export default {
  name: "app",
  components: {
    Marketing
  }
};
</script>

<style lang="scss">
#app {
  width: 1200px;
  margin: 0 auto;
}
@media screen and (max-width: 1200px) {
  #app {
    width:auto;
    padding:0 20px;
  }
}

@media screen and (max-width: 576px) {
  #app {
    padding:0 7px;
  }
}
</style>
