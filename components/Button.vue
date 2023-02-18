<template>
  <div>
    <button @click="toggle">Button</button>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        toggler: false
      }
    },
    methods: {
      toggle() {
        alert('clicked')
        this.toggler = !this.toggler;
      }
    }
  }
</script>

<style>

</style>