<template lang="pug">
  div.box
    p {{ msg }}
    child-component
</template>

<script>
import ChildComponent from './child-component.vue';

export default {
  components: { ChildComponent },

  data() {
    return: {
      msg: 'Hello Vue.js!'
    }
  }
}
</script>

<style lang="scss" scoped>
  .box {
    width: 30%;
    p {
      color: red;
    }
  }
</style>
