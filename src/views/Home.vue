<template>
  <div>
    <div>
      <the-first-view-section></the-first-view-section>
    </div>
    <div>
      <the-about-section></the-about-section>
    </div>
    <div>
      <the-event-section></the-event-section>
    </div>
    <div>
      <the-team-section></the-team-section>
    </div>
    <div>
      <the-rec-event-section></the-rec-event-section>
    </div>
    <div>
      <the-info-section></the-info-section>
    </div>
    <div>
      <the-requirements-section></the-requirements-section>
    </div>
    <div>
      <contact-section></contact-section>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import TheFirstViewSection from '@/components/sections/TheFirstView.vue'
import TheAboutSection from '@/components/sections/TheAboutSection.vue'
import TheEventSection from '@/components/sections/TheEventSection.vue'
import TheTeamSection from '@/components/sections/TheTeamSection.vue'
import TheRecEventSection from '@/components/sections/TheRecEventSection.vue'
import TheInfoSection from '@/components/sections/TheInfoSection.vue'
import TheRequirementsSection from '@/components/sections/TheRequirementsSection.vue'
import ContactSection from '@/components/sections/ContactSection.vue'

export default {
  name: 'Home',
  components: {
    TheFirstViewSection,
    TheAboutSection,
    TheEventSection,
    TheTeamSection,
    TheRecEventSection,
    TheInfoSection,
    TheRequirementsSection,
    ContactSection,
  }
}
</script>
