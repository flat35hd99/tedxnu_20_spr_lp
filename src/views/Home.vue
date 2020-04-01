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
  },
  mounted: function () {
    const title = '求む、熱意ある学生 | TEDxNagoyaU'
    const description = 'TEDxNagoyaUは名古屋大学でTEDxイベントを運営する学生のみで構成されたイベント運営団体です。'
    document.title = title
    document.querySelector("meta[property='og:title']")
      .setAttribute('content', title)
    document.querySelector("meta[name='description']")
      .setAttribute('content', description)
    document.querySelector("meta[property='og:description']")
      .setAttribute('content', description)
  }
}
</script>
