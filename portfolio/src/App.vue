<template>
  <MyHeader></MyHeader>
  <MyPresentation></MyPresentation>
  <MyTimeline></MyTimeline>
  <SoftSkill></SoftSkill>

</template>

<script>
import MyHeader from "@/components/MyHeader";
import MyPresentation from "@/components/MyPresentation";
import MyTimeline from "@/components/MyTimeline";
import SoftSkill from "@/components/SoftSkill";

export default {
  name: 'App',
  components: {
    MyHeader,
    MyPresentation,
    MyTimeline,
    SoftSkill,
  }
}
</script>

<style>
#app {
}
</style>
