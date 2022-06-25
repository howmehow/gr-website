<template>
  <div class="cv">
    <v-row>
      <v-spacer></v-spacer>
      <v-col class="ma-0 pa-0" cols="6">
        <v-img :src="experience" max-height="906px" max-width="819px"></v-img>
      </v-col>
      <v-col class="ma-0 pa-0" cols="4">
        <v-img :src="education" max-height="874px" max-width="573px"></v-img>
      </v-col>
      <v-col class="ma-0 pa-0" cols="2">
        <v-img :src="skills" max-height="874px" max-width="326px"></v-img>
      </v-col>
      <v-spacer></v-spacer>
    </v-row>
    <v-row>
      <v-img :src="hobbies" max-height="174px" max-width="1098px"></v-img>
    </v-row>
    <v-row class="py-16">
      <v-card-text>{{ text }}
      </v-card-text>
    </v-row>
    <v-row class="py-16" justify="center">
      <div class="ma-3">
        <v-img :src="gmailIcon" max-height="20" max-width="20"></v-img>
      </div>
      <a :href="gmailTextMail" class="pa-2" rel="noopener" target="_blank">{{ gmailText }}</a>
    </v-row>
    <v-row justify="center">
      <div class="ma-3">
        <v-img :src="linkedInDarkIcon" max-height="20" max-width="20"></v-img>
      </div>
      <a :href="linkedInText" class="pa-2" rel="noopener" target="_blank">{{ linkedInText }}</a>
    </v-row>
    <v-row justify="center">
      <div class="ma-3">
        <v-img :src="mediumIcon" max-height="20" max-width="20"></v-img>
      </div>
      <a :href="mediumText" class="pa-2" rel="noopener" target="_blank">{{ mediumText }}</a>
    </v-row>
    <v-row justify="center">
      <div class="ma-3">
        <v-img :src="portfolioIcon" max-height="20" max-width="20"></v-img>
      </div>
      <p>Portfolio: <a :href="notionText" class="pa-2" rel="noopener" target="_blank">Notion</a> <a
        :href="figmaText" class="pa-2" rel="noopener" target="_blank">Figma</a></p>
    </v-row>
    <v-row justify="center">
      <div class="ma-3 mb-16">
        <v-img :src="dribbleDarkIcon" max-height="20" max-width="20"></v-img>
      </div>
      <a :href="dribbleText" class="pa-2" rel="noopener" target="_blank">{{ dribbleText }}</a>
    </v-row>
  </div>
</template>

<script>
export default {
  name: "CV",
  data: () => {
    return {
      experience: '/personal/cv/experience.png',
      education: '/personal/cv/education.png',
      skills: '/personal/cv/skills.png',
      hobbies: '/personal/cv/hobbies.png',
      gmailIcon: '/icons/gmail.png',
      dribbleDarkIcon: '/icons/dribbleDark.png',
      linkedInDarkIcon: '/icons/linkedInDark.png',
      mediumIcon: '/icons/mediumIcon.png',
      portfolioIcon: '/icons/portfolioDark.png',

      text: 'An intuitive, reliable and cheerful designer who enjoys solving problems. With a degree in Fine Arts, finally sees with new eyes how all this knowledge can be developed constructively and satisfyingly. The aim is not only to enjoy a vocation but to deepen her understanding of how the market works. And even more, the impact it has on users through the application of UX/UI design.',
      gmailText: 'gloriarosssi@gmail.com',
      gmailTextMail: 'mailto:gloriarosssi@gmail.com',
      linkedInText: 'https://www.linkedin.com/in/gloriarossisanahuja',
      mediumText: 'https://medium.com/@gloriarossi',
      portfolioText: 'Portfolio: Notion    Figma  ',
      notionText: 'https://gloriarossi.notion.site/Gloria-Rossi-14c25d6ab0fd470bb718131483ffc956',
      figmaText: 'https://www.figma.com/proto/HluiqMsKeJ1lGfFUwcnzRQ/Gloria-Rossi\'s-Portfolio?page-id=5%3A5&node-id=6%3A178&viewport=260%2C48%2C0.03&scaling=min-zoom&starting-point-node-id=6%3A178',
      dribbleText: 'https://dribbble.com/Glorossa/shots',
    }
  }

}
</script>

<style scoped>
.cv {
  padding: 0 !important;
}
</style>
