<template>
  <section>
    <main-header />
    <main-intro />
    <options-preview />
    <main-description />
    <main-review />
  </section>
</template>

<script>
import MainDescription from './components/main-description.vue'
import mainHeader from "./components/main-header.vue"
import mainIntro from './components/main-intro.vue'
import OptionsPreview from './components/options-preview.vue'
import MainReview from './components/main-review.vue'

export default {
  components: { mainHeader, mainIntro, OptionsPreview, MainDescription, MainReview }
}
</script>

<style>
</style>