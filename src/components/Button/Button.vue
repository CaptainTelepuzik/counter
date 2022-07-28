<template src="./template.html"/>
<script>
export default {
  name: "V-Button",
  methods: {
    _changeButton(value) {
      this.$emit('ChangeCounter',value);
    },
  }
}
</script>

<style scoped src="./style.scss" lang="scss"></style>