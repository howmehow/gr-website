<template>
  <div>
    <v-row>
      <v-col>
        <div class="text-center">
          <v-menu
            :top="top"
            offset-y
            open-on-hover
          >
            <template #activator="{ on, attrs }">
              <v-btn
                :ripple="{ class: 'white--text' }"
                depressed
                plain
                retain-focus-on-click

                text
                v-bind="attrs"
                v-on="on"
              >
                CASE STUDY
              </v-btn>
            </template>

            <v-list>
              <v-list-item
                v-for="(item, index) in items"
                :key="index"
              >
                <v-list-item-title>
                  <v-btn
                    :ripple="{ class: 'white--text' }"
                    :to="item.link"
                    depressed
                    plain
                    retain-focus-on-click
                    text
                  >
                    {{ item.title }}
                  </v-btn>
                </v-list-item-title>
              </v-list-item>
            </v-list>
          </v-menu>
        </div>
      </v-col>
      <v-col>
        <v-btn
          :ripple="{ class: 'white--text' }"

          aria-label="GALLERY"
          class="text-no-wrap"
          depressed
          plain
          retain-focus-on-click
          text

          to="/PortfolioGallery"
        >GALLERY
        </v-btn
        >
      </v-col>
      <v-col>
        <v-btn
          :ripple="{ class: 'white--text' }"

          aria-label="AboutMe"
          class="text-no-wrap"
          depressed
          plain
          retain-focus-on-click
          text

          to="/AboutMe"
        >ABOUT ME
        </v-btn
        >
      </v-col>
      <v-col>
        <v-btn
          :ripple="{ class: 'white--text' }"

          aria-label="CV"
          class="text-no-wrap"
          depressed
          plain
          retain-focus-on-click
          text

          to="/CV"
        >CV
        </v-btn
        >
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: "DirectionLinks",
  props: {
    top: {
      default: false,
      type: Boolean,
    }
  },
  data: () => ({
    items: [
      {title: 'Trödel Spende', link: '/CaseStudyTrodel'},
      {title: 'Filin', link: '/CaseStudyFilin'},
      {title: 'Art & Yoga', link: '/CaseStudyArtYoga'},
    ],
  }),
}
</script>

<style scoped>

</style>
