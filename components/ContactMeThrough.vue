<template>
  <div>
    <v-row>
      <DirectionLinks :top="true"></DirectionLinks>
    </v-row>
    <v-row>
      <v-col>
        <a
          href="https://www.linkedin.com/in/gloriarossisanahuja" rel="noopener" target="_blank">
          <v-img
            :src="linkedInIcon"
            max-height="30" max-width="30"></v-img>
        </a>
      </v-col>
      <v-col>
        <a href="https://medium.com/@gloriarossi" rel="noopener" target="_blank">
          <v-img
            :src="mediumIcon"
            max-height="30" max-width="30"></v-img>
        </a>
      </v-col>
      <v-col>
        <a
          href="https://gloriarossi.notion.site/gloriarossi/Gloria-Rossi-14c25d6ab0fd470bb718131483ffc956"
          rel="noopener" target="_blank">
          <v-img
            :src="notionIcon"
            max-height="30" max-width="30"></v-img>
        </a>
      </v-col>

      <v-col>
        <a href="https://dribbble.com/Glorossa/shots" rel="noopener" target="_blank">
          <v-img
            :src="dribbleIcon"
            max-height="30" max-width="30"></v-img>
        </a>
      </v-col>
    </v-row>

  </div>
</template>

<script>
export default {
  name: "ContactMeThrough",
  data: () => {
    return {
      linkedInIcon: '/icons/linkedInIcon.svg',
      dribbleIcon: '/icons/dribbleIcon.png',
      mediumIcon: '/icons/mediumIcon.png',
      notionIcon: '/icons/notionIcon.png'
    }
  }
}
</script>

<style scoped>

</style>
