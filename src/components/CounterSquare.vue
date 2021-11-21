<template>
  <div class="counter-squared">
    {{ $store.state.counter }}
    <sup>2</sup> =
<!--    TODO два варианта записи-->
<!--    {{ $store.getters.counterSquared}}-->
    {{counterSquared}}
  </div>
</template>

<script>

import {mapGetters} from 'vuex';

export default {
  name: "CounterSquare",
  computed: {
    ...mapGetters({
      // имя можно менять 'counterSquared'
      counterSquared: 'counterSquared'
    })
  }
}
</script>

<style scoped>

</style>
