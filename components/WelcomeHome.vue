<template>
  <div class="welcome-home">
    <v-row>
      <v-card-title>Welcome to my website</v-card-title>
    </v-row>
    <v-row>
      <v-card-text>I am a Spanish Ux/Ui Designer, a Polytechnic University of Valencia artist graduate and a
        horticulture enthusiast.

        I work with different principles and methods like the ‘Design Process Thinking’ or the ‘Crazy 8’. Always aiming
        to achieve -as Jared Spool would say- an invisible design that helps and attracts users.

        If you would like to get in touch, please message me on LinkedIn or by email at gloriarossi@pm.me; And don’t
        hesitate on checking my Dribbble and Medium accounts.

        You can also have a look at my portfolio in Notion
      </v-card-text>
    </v-row>
    <ProjectsGrid></ProjectsGrid>
    <AboutMeWelcomePage></AboutMeWelcomePage>
  </div>

</template>

<script>

export default {
  name: "WelcomeHome",
}
</script>

<style scoped>
.welcome-home {
  margin: 100px;
}
</style>
