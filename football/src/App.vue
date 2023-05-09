<script>
import headerVue from '../src/components/haeder.vue';
import mainVue from '../src/components/main.vue';
import footerVue from '../src/components/footer.vue';


export default {
  name: 'App',
  components: {
    headerVue,
    mainVue,
    footerVue,
  }
}
</script>

<template>
  <div id="cursor">
    <headerVue />
    <mainVue />
    <footerVue />
  </div>  
</template>

<style lang="scss" scoped>
  
</style>