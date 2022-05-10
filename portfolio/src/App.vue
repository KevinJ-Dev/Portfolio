<template>
  <MyHeader></MyHeader>
  <MyPresentation></MyPresentation>
  <MyTimeline></MyTimeline>
  <SoftSkill></SoftSkill>
  <MyProject></MyProject>
  <MyForm></MyForm>
  <MyFooter></MyFooter>

</template>

<script>
import MyHeader from "@/components/MyHeader";
import MyPresentation from "@/components/MyPresentation";
import MyTimeline from "@/components/MyTimeline";
import SoftSkill from "@/components/SoftSkill";
import MyProject from "@/components/MyProject";
import MyForm from "@/components/MyForm";
import MyFooter from "@/components/MyFooter";

export default {
  name: 'App',
  components: {
    MyHeader,
    MyPresentation,
    MyTimeline,
    SoftSkill,
    MyProject,
    MyForm,
    MyFooter,
  }
}
</script>

<style>
#app {
}
</style>
