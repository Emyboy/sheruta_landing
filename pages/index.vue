<template>
  <div>
    <AgentHero />
    <about-us-component />
    <our-numbers />
    <AgentBenefits />
  </div>
</template>

<script>
import AboutUsComponent from '~/components/Home/AboutUsComponent.vue'
import OurNumbers from '~/components/Home/OurNumbers.vue'
export default {
  components: { OurNumbers, AboutUsComponent },
  name: 'IndexPage',
}
</script>
