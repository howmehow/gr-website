<template>
  <div>
    <v-img :src="filinHeader" class="header"></v-img>
    <v-spacer></v-spacer>
    <v-container class="links-container">
      <h2>Filin MVP</h2>
      <v-container class="links">
        <v-row>
          <v-col class="pa-0"><a href="#planning">Planning</a></v-col>
          <v-col class="pa-0"><a href="#siteMap">Site Map</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a href="#brief">Brief</a></v-col>
          <v-col class="pa-0"><a href="#wireframesAndPrototypes">Wireframes and prototypes</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a class="indent" href="#competitiveBusinessAnalysis">Competitive Business analysis</a>
          </v-col>
          <v-col class="pa-0"><a class="indent" href="#crazy8s">Crazy 8s</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a class="indent" href="#qualitativeAndQuantitativeResearch">Qualitative and Quantitative
            Research</a>
          </v-col>
          <v-col class="pa-0"><a class="indent" href="#loFiWireframe">Lo-fi wireframe</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a href="#affinityMapAndEmpathyMap">Affinity Map and Empathy Map</a></v-col>
          <v-col class="pa-0"><a class="indent" href="#loFiPrototype">Lo-fi prototype</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a href="#persona">Persona</a></v-col>
          <v-col class="pa-0"><a class="indent" href="#midFiWireframe">Mid-fi wireframe</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a href="#brandingMoodBoardStyle">Branding, Mood board, Style Tile, Style Guide</a>
          </v-col>
          <v-col class="pa-0"><a class="indent" href="#hiFiWireframe">Hi-fi wireframe</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a href="#"></a></v-col>
          <v-col class="pa-0"><a href="#hiFiFinalMVP">Hi-fi final MVP</a></v-col>
        </v-row>
      </v-container>
    </v-container>
    <v-container class="text-container">
      <h2 id="planning">Planning</h2>
      <p>For this project, I tried to condense the UX Research on the first days, and leave the UI for the second week.
        Due to a condensed schedule, I wasn’t able to do all the things I had in mind, but I prioritised and focused on
        the most needed tasks.</p>
      <v-img :src="filinPlanning"></v-img>
    </v-container>
    <v-container class="text-container">
      <h2 id="brief">Brief</h2>
      <p>Our client for the week five project was The National Wellness Institute. Our brief was clear: we had to
        conduct user research to understand people’s relationship with mental, physical, and emotional well-being to
        develop a tool driving them to action. We had to focus on the main aspect: it tracks the user’s progress and
        pushes them to commit to a healthier lifestyle. We could focus on any category related to that aspect: exercise
        and fitness, eating/diet, meditation, time management, etc.</p>
      <h2 id="qualitativeAndQuantitativeResearch">Qualitative and Quantitative Research</h2>
      <p>I had in mind to build an app to create teams. Socialising meanwhile exercising. I tailored a survey of
        thirteen questions and gathered some information about wellness in sports. For the users, the most important
        meaning of the sport was considered Mental health, followed by fitness and fun/ pleasure. But I found out that
        66% of the users prefer solo.</p>
      <h2 id="">From all the surveys</h2>
      <ul>
        <li>80% love sport</li>
        <li>66% do sport solo</li>
        <li>54% don’t share on social media</li>
        <li>50% set goals occasionally</li>
        <li>50% don’t set up a goal</li>
      </ul>
      <p>I went a step further and tried to do more extensive research. Moreover, I conducted two interviews. The first
        one was with a user and the second one with an expert. From my findings, both were using apps. The user is using
        the one given by the gym. The key points I used from both interviews were:</p>
      <ul>
        <li>Sport helps to be mentally healthier, promotes a BALANCE</li>
        <li>The problem to do team sports is matching schedules</li>
        <li>Is needed routine to AVOID injuries, problems with breathing and even throat</li>
        <li>Routines can’t be generalised. Depends on age, gender, previous experience, your GOALS</li>
      </ul>
      <v-img :src="filinColourSpectrum"></v-img>
    </v-container>
    <v-container class="text-container">
      <h2 id="competitiveBusinessAnalysis">Competitive Business analysis</h2>
      <p>I did some research on the offers that are nowadays in the market. They are many apps that help establish this
        relationship between fitness and eating habits. I compared the most used in Google play and I did a competitive
        analysis to figure out what they offer and visual analysis. In the visual analysis, we can see how the colours
        used are saturated and they use between 4 to 3 colours, except Nike that stays sober with his black and
        white.</p>
      <v-img :src="filinBusinessAnalysis"></v-img>
    </v-container>
    <v-container class="text-container">
      <h2 id="affinityMapAndEmpathyMap">
        Affinity and Empathy Map
      </h2>
      <v-img :src="filinMap"></v-img>
      <v-img :src="filinMap2"></v-img>
      <p><a href="https://unsplash.com/@benjaminsweet">Photo by https://unsplash.com/@benjaminsweet</a></p>
    </v-container>
    <v-container class="text-container">
      <h2
        id="persona">Persona</h2>
      <p> This persona will be the one to use the user journey and the user flow. Let me introduce you to Sophia, a
        strong woman between 30 and 39 years old and busy. She tries to keep the balance in her life, and she uses sport
        for it.</p>
      <v-img :src="filinPersona"></v-img>
      <p>Persona. Images: various from Unsplash. Woman:<a href="https://unsplash.com/@kultbrecher">https://unsplash.com/@kultbrecher</a>
      </p>
    </v-container>
    <v-container class="text-container">
      <h2 id="brandingMoodBoardStyle">Branding, Moodboard, Style Tile, Style Guide</h2>
      <p>I wrote down the branding I wanted to represent for my MVP. It does make a difference to have some aspects of
        the branding clear.</p>
      <v-img :src="filinBranding2"></v-img>
      <v-img :src="filinBranding"></v-img>
      <p>Branding Attributes (Beaver
        characteristics[https://spiritsofthewestcoast.com/collections/the-beaver-symbol](https://spiritsofthewestcoast.com/collections/the-beaver-symbol))</p>
      <p>With the moodboard, I chose warm colours and I build a composition that could imply the attributes of the
        brand. Sport also balances the body and mental health.</p>
      <v-img :src="filinDancer"></v-img>
    </v-container>

  </div>
</template>

<script>
export default {
  name: "CaseStudyFilin",
  data: () => {
    return {
      filinHeader: '/projects/filin/filinHeader.png',
      filinPlanning: '/projects/filin/filinPlanning.png',
      filinColourSpectrum: '/projects/filin/filinColourSpectrum.png',
      filinBusinessAnalysis: '/projects/filin/filinBusinessAnalysis.png',
      filinMap: '/projects/filin/filinMap.png',
      filinMap2: '/projects/filin/filinMap2.png',
      filinPersona: '/projects/filin/filinPersona.png',
      filinBranding: '/projects/filin/filinBranding.png',
      filinBranding2: '/projects/filin/filinBranding2.png',
      filinDancer: '/projects/filin/filinDancer.png'
    }
  }
}
</script>

<style scoped>
.links-container {
  margin-left: 30%;
  width: 50%;
}

.links {
  margin-left: 20px;
}

.indent {
  margin-left: 1em;
}

.text-container {
  padding-left: 20%;
  padding-right: 20%;
}

</style>
