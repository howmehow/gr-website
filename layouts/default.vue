<template>
  <v-app dark>
    <NavBar></NavBar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>

  <FooterBar></FooterBar>
  </v-app>
</template>

<script>
import NavBar from '../components/NavBar'
import FooterBar from "@/components/FooterBar";
export default {
  components: {
    NavBar,
    FooterBar,
  },
  name: 'DefaultLayout',
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
      title: 'Vuetify.js'
    }
  }
}
</script>
