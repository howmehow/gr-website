<template>
  <v-app dark>
    <NavBar></NavBar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>

  <TheFooter></TheFooter>
  </v-app>
</template>

<script>
import NavBar from '../components/NavBar'
import TheFooter from "@/components/TheFooter";
export default {
  name: 'DefaultLayout',
  components: {
    NavBar,
    TheFooter,
  },
  data () {

    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Gloria Rossi website'
    }
  }
}
</script>
