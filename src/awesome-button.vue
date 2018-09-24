<template>
  <button @click="alert">yo</button>
</template>

<script>
export default {
  methods: {
    alert() {
      window.alert('hello world');
    },
  },
}
</script>
