<template>
 <div>
    <page-head></page-head>
    <page-main></page-main>
    <page-foot></page-foot>
 </div>
</template>

<script>
import PageHeadVue from './components/PageHead.vue';
import PageMainVue from './components/PageMain.vue';
import PageFootVue from './components/PageFoot.vue';
export default {
  name: 'App',
  components: {
    PageHeadVue, PageMainVue, PageFootVue
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
