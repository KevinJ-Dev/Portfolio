<template>
  <MyHeader></MyHeader>
  <MyPresentation></MyPresentation>
  <MyTimeline></MyTimeline>
  <SoftSkill></SoftSkill>
  <MyProject></MyProject>
  <MyFooter></MyFooter>

</template>

<script>
import MyHeader from "@/components/MyHeader";
import MyPresentation from "@/components/MyPresentation";
import MyTimeline from "@/components/MyTimeline";
import SoftSkill from "@/components/SoftSkill";
import MyProject from "@/components/MyProject";
import MyFooter from "@/components/MyFooter";

export default {
  name: 'App',
  components: {
    MyHeader,
    MyPresentation,
    MyTimeline,
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
