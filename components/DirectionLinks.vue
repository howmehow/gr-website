<template>
  <div>
    <v-row>
      <v-col>

        <NuxtLink
          aria-label="CASE STUDY"
          class="text-no-wrap"

          to="/CaseStudyArtYoga"
        >CASE STUDY
        </NuxtLink
        >
      </v-col>
      <v-col>
        <NuxtLink
          aria-label="GALLERY"
          class="text-no-wrap"

          to="/PortfolioGallery"
        >GALLERY
        </NuxtLink
        >
      </v-col>
      <v-col>
        <NuxtLink
          aria-label="AboutMe"
          class="text-no-wrap"

          to="/AboutMe"
        >ABOUT ME
        </NuxtLink
        >
      </v-col>
      <v-col>
        <NuxtLink
          aria-label="CV"
          class="text-no-wrap"

          to="/CV"
        >CV
        </NuxtLink
        >
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: "DirectionLinks"
}
</script>

<style scoped>

</style>
