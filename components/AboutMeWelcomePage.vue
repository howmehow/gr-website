<template>
  <div>
    <v-row>
      <v-card-title>{{ title }}</v-card-title>
    </v-row>
    <v-row>
      <v-card-text> {{ text }}
      </v-card-text>
    </v-row>
    <v-row justify="center">
      <v-img
        max-height="150"
        max-width="150" src="/personal/profilePhoto.png"></v-img>
    </v-row>


  </div>
</template>

<script>
export default {
  name: "AboutMeWelcomePage",
  data: () => {
    return {
      title: 'About me',
      text: 'I am a UX/UI Designer with an artistic background.\n' +
        '\n' +
        '      I was born near Valencia, Spain, where the mountains meet the sea and the orange orchards.\n' +
        '\n' +
        '      I’ve lived in Spain, England and Scotland, Germany and Poland. And I wouldn’t mind a fifth country 😀 .\n' +
        '\n' +
        '      So by now I speak Spanish, Catalan, fluent English, ein bisschen Deutsch i odrobinę po polsku.\n' +
        '\n' +
        '      I studied a Bachelor\'s in Fine Arts and I have a Master\'s in Artistic Production both at the Polytechnic\n' +
        '      University of Valencia. Art moves my soul.\n' +
        '\n' +
        '      I started studying UX/UI in Berlin earlier this year. I\'m very critical of the apps and websites I choose to use\n' +
        '      and that made me realise that, once I\'ve trained my observant eye, it\'s very hard to give it up.\n' +
        '\n' +
        '      I love hiking and horticulture. It fascinates me how a seed can become so much, is like design, from a thought we\n' +
        '      can create a practical interactive page.'
    }
  }
}
</script>

<style scoped>

</style>
