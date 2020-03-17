<template>
  <section class="header">
    <h1>I am learning VueJS</h1>
    <span>with help of my Mentor</span>
    <p>Testing the a = {{ a }}</p>
    <p> obj = {{ obj }}</p>
  </section>
</template>

<script>

const dss = '4'

export default {
  data() {
    return {
      a: 123,
      b: "переменная б",
      obj: {
        a: 1222, b: 2, c: 3, d: dss
      }
    }
  }
};
</script>

<style>

  section { 
    display: block;
  }
  .header {
    border-color: coral;
  }
</style>
