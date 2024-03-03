<template>
  <HeadComp></HeadComp>
  <InputSection></InputSection>
 
  <RemoveBtn v-show="false"></RemoveBtn>
</template>

<script>
import HeadComp from './components/HeadComp.vue';
import RemoveBtn from './components/RemoveBtn.vue';
import InputSection from './components/InputSection.vue';


export default {
  name: 'App',
  components: {
    HeadComp,
    RemoveBtn,
    InputSection
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  
}
</style>
