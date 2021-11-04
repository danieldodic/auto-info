<template>
  <section>
    <o-button @click="clickMe">Click Me</o-button>
  </section>
</template>

<script>
export default {
    methods: {
      clickMe() {
        alert('Clicked!')
      }
    }
  }

</script>
