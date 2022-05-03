<template>
  <MyHeader></MyHeader>
  <MyPresentation></MyPresentation>
<!--  <img alt="Vue logo" src="./assets/logo.png">-->
</template>

<script>
import MyHeader from "@/components/MyHeader";
import MyPresentation from "@/components/MyPresentation";

export default {
  name: 'App',
  components: {
    MyHeader,
    MyPresentation,
  }
}
</script>

<style>
#app {
}
</style>
