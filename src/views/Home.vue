<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Counter/>
    <CounterSquare />
    <Buttons />
    <ColorCode />
  </div>
</template>

<script>
import Counter from "../components/Counter";
import CounterSquare from "../components/CounterSquare";
import Buttons from "../components/Buttons";
import ColorCode from "../components/ColorCode";

export default {
  name: 'Home',
  components: {
    Counter,
    CounterSquare,
    Buttons,
    ColorCode
  }
}
</script>

<style>
div {
  margin-bottom: 10px;
}
.counter {
  font-size: 80px;
}
.buttons button {
  font-size: 40px;
  width: 100px;
  margin: 0 10px;
}
</style>
