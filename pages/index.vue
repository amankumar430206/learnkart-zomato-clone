<template>
  <div class="app-wrapper">
    <Section-header />
    <section-suggestion />
    <Section-collections />
    <Section-localities />
    <section-get-app />
    <section-explore />
    <app-footer />
  </div>
</template>

<script>
import SectionLocalities from '../components/sectionLocalities.vue'
import SectionCollections from '~/components/sectionCollections.vue'
import SectionHeader from '~/components/sectionHeader.vue'
import SectionSuggestion from '~/components/sectionSuggestion.vue'
import SectionGetApp from '~/components/sectionGetApp.vue'
import SectionExplore from '~/components/section-explore.vue'
import AppFooter from '~/components/appFooter.vue'
export default {
  name: 'IndexPage',
  components: {
    SectionCollections,
    SectionLocalities,
    SectionHeader,
    SectionSuggestion,
    SectionGetApp,
    SectionExplore,
    AppFooter,
  },
}
</script>

<style lang="scss">
.container {
  max-width: 1080px;
}
.icon {
  width: 16px;
  height: auto;
}

.heading-md {
  font-weight: 400;
}
</style>
