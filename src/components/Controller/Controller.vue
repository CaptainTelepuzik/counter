<template src="./template.html"/>

<script>

import Display from "@/components/Display/Display";
import Button from "@/components/Button/Button";

export default {
  name: "V-Controller",
  components: {
    Display,
    Button
  },
  data(){
    return{
      counter: 0
    }
  },
  methods:{
    changeCounter(value) {
      this.counter+=value;
    },
  }
}
</script>


<style scoped src="./style.scss" lang="scss"></style>