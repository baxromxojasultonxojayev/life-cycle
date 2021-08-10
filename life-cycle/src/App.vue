<template>

  <section-one></section-one>
  <section-two></section-two>
  <section-three></section-three>
</template>

<script>
import SectionOne from './components/SectionOne.vue'
import SectionTwo from './components/SectionTwo.vue'
import SectionThree from './components/SectionThree.vue'
export default {
  components: {
    SectionOne,
    SectionTwo,
    SectionThree
  },
  data() {
   return{
   }
 }
}
</script>

<style>
.main{
  /* height: 200px; */
}
</style>