<template>
  <section class="container">
    <test-component />
  </section>
</template>

<script>
import TestComponent from 'vue-ssr-repro-component'

export default {
  components: {
    TestComponent
  }
}
</script>

<style>
.container
{
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
