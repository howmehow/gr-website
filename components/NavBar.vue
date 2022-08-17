<template>
  <div>
    <v-card class="overflow-hidden">
      <v-app-bar
        absolute
        class="white"
        elevate-on-scroll
        extended
        scroll-target="#scrolling-techniques-7"
      >
        <!--      <v-app-bar-nav-icon></v-app-bar-nav-icon>-->
        <NuxtLink
          aria-label="Homepage"
          class=""
          to="/"
        >
          <v-img :src="img"></v-img>
        </NuxtLink
        >

        <v-spacer></v-spacer>

        <DirectionLinks></DirectionLinks>
      </v-app-bar>
      <v-sheet
        id="scrolling-techniques-7"
        class="overflow-y-auto"
        max-height="600"
      >
        <v-container style="height: 70px;">
        </v-container>
      </v-sheet>
    </v-card>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  data: () => {
    return {
      img: 'personal/signature.svg',
    }
  }

}
</script>

<style scoped>

</style>
