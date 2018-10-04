<template>
  <h1 :class="$style.test">What's wrong?</h1>
</template>

<style module>
.test {
  color: red;
}
</style>

<script>
export default {
  name: 'test',
  created() {
    console.log(this.$style.test);
  },
}
</script>
