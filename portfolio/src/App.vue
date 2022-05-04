<template>
  <MyHeader></MyHeader>
  <MyPresentation></MyPresentation>
  <SoftSkill></SoftSkill>

</template>

<script>
import MyHeader from "@/components/MyHeader";
import MyPresentation from "@/components/MyPresentation";
import SoftSkill from "@/components/SoftSkill";

export default {
  name: 'App',
  components: {
    MyHeader,
    MyPresentation,
    SoftSkill,
  }
}
</script>

<style>
#app {
}
</style>
