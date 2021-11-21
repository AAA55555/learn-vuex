<template>
  <div class="buttons">
    <button @click="this.$store.dispatch('decreaseCounter')">-</button>
    <button @click="this.$store.dispatch('increaseCounter')">+</button>
  </div>
</template>

<script>
export default {
  name: "Buttons"
}
</script>

<style scoped>

</style>
