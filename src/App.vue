<template>
 <landing-homepage></landing-homepage>
 <landing-analytics></landing-analytics>
 <landing-benefits></landing-benefits>
 <landing-collaborate></landing-collaborate>
 <landing-features></landing-features>
 <landing-integration></landing-integration>
 <landing-pricing></landing-pricing>
</template>

<script>
import LandingAnalytics from './pages/components/LandingAnalytics.vue';
import LandingBenefits from './pages/components/LandingBenefits.vue';
import LandingCollaborate from './pages/components/LandingCollaborate';
import LandingFeatures from './pages/components/LandingFeatures.vue';
import LandingHomepage from './pages/components/LandingHomepage.vue';
import LandingIntegration from './pages/components/LandingIntegration.vue';
import LandingPricing from './pages/components/LandingPricing'

export default {
  name: 'App',
  components: {
    LandingAnalytics,
    LandingBenefits,
    LandingCollaborate,
    LandingFeatures,
    LandingHomepage,
    LandingIntegration,
    LandingPricing,

  }
}
</script>

<style>
#app {
  display: grid;
  grid-template: 6, 1fr;
  width: 100vw;
  
 
 
}
</style>
