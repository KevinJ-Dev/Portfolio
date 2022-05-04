<template>
  <MyHeader></MyHeader>
  <MyPresentation></MyPresentation>
  <SoftSkill></SoftSkill>
  <MyProject></MyProject>
  <MyFooter></MyFooter>

</template>

<script>
import MyHeader from "@/components/MyHeader";
import MyPresentation from "@/components/MyPresentation";
import SoftSkill from "@/components/SoftSkill";
import MyProject from "@/components/MyProject";
import MyFooter from "@/components/MyFooter";

export default {
  name: 'App',
  components: {
    MyHeader,
    MyPresentation,
    SoftSkill,
    MyProject,
    MyFooter,
  }
}
</script>

<style>
#app {
}
</style>
