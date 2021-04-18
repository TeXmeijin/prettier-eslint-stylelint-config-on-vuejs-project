<template>
  <div>
    <h1>heading</h1>
    <p>This sentence is over 80 characters. aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</p>
    <p>
      This sentence is over 120 characters. aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
    </p>
    <p>{{ label }}</p>
  </div>
</template>

<script>
import Vue from 'vue'

export default Vue.extends({
  data() {
    return {
      label: 'hello',
    }
  },
})
</script>

<style lang="scss" scoped>
div {
  font-size: .9rem;
}
</style>
