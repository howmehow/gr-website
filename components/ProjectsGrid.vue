<template>
  <div>
    <div v-for="project in projects" :key="project.id">
      <v-row>
        <v-col><a :href="project.link"><img :src='project.img' alt="project-img"></a></v-col>
        <v-col>
          <v-card-title>{{ project.title }}</v-card-title>
          <v-card-text>{{ project.info }}</v-card-text>
        </v-col>
      </v-row>


    </div>

  </div>
</template>

<script>
export default {
  name: "ProjectsGrid",
  data: () => {
    return {
      projectsHeading: 'Projects Portfolio',
      projectsDescription: 'Some of the projects I have successfully completed',
      projects: [
        {
          id: 'trodelSpende',
          title: 'TrödelSpendes MVP',
          type: 'UX | UI | Figma | planning',
          info: 'Time: 4 months\n' +
            'Team: Berna Akpinar, Carolina Torres, Gloria Rossi\n' +
            'Stakeholder: Trödel Spende',
          img: 'projects/trodelSpende/trodelSpende.png',
          link: '/',
        },
        {
          id: 'filin',
          title: 'FILIN',
          type: 'UX | UI | Figma | planning |MVP',
          info: 'Time: 2 weeks\n' +
            'Team: Gloria Rossi',
          img: 'projects/filin/filinHeader.png',
          link: '/',
        },
        {
          id: 'artAndYoga',
          title: 'Art & Yoga',
          type: 'UX | UI | Figma | planning',
          info: 'Time: 1 week\n' +
            'Team: Miriam Monleon, Javi Calvert, Gloria Rossi\n' +
            'Stakeholder: Art&Yoga',
          img: 'projects/artAndYoga/artAndYoga.png',
          link: '/',
        },
      ],
    }
  }
}
</script>

<style scoped>

</style>
