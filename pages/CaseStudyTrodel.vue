<template>
  <div>
    <v-img :src="trodelSpendeHeader" class="header"></v-img>
    <v-spacer></v-spacer>
    <v-container class="links-container">
      <h2>Trödel Spende MVP</h2>
      <v-container class="links">
        <v-row>
          <v-col class="pa-0"><a href="#company">Company</a></v-col>
          <v-col class="pa-0"><a href="#moodBoard">Mood board</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a href="#brief">Brief</a></v-col>
          <v-col class="pa-0"><a class="indent" href="#styleTile">Style Tile</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a href="#gettingToWork">Getting to work</a></v-col>
          <v-col class="pa-0"><a class="indent" href="#styleGuide">Style Guide</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a class="indent" href="#surveyAndInterviewInsights">Survey and interview insights</a>
          </v-col>
          <v-col class="pa-0"><a class="indent" href="#siteMap">Site Map</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a class="indent" href="#competitorsAnalysis">Competitors Analysis</a></v-col>
          <v-col class="pa-0"><a href="#wireframesAndPrototypes">Wireframes and prototypes</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a class="indent" href="#painsAndGoals">Pains and goals</a></v-col>
          <v-col class="pa-0"><a class="indent" href="#loFi">Lo-fi </a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a href="#persona">Persona</a></v-col>
          <v-col class="pa-0"><a class="indent" href="#midFi">Mid-fi </a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a class="indent" href="#moscowMethod">MOSCOW method</a></v-col>
          <v-col class="pa-0"><a class="indent" href="#hiFi">Hi-fi </a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a class="indent" href="#hypothesisStatement">Hypothesis Statement</a></v-col>
          <v-col class="pa-0"><a href="#hiFiFinalMvp">Hi-fi final MVP</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a href="#"></a></v-col>
          <v-col class="pa-0"><a href="#implementation">Implementation</a></v-col>
        </v-row>
        <v-row>
          <v-col class="pa-0"><a href="#"></a></v-col>
          <v-col class="pa-0"><a href="#nextSteps">Next Steps</a></v-col>
        </v-row>
      </v-container>
    </v-container>
    <v-container class="text-container">
      <h2 id="company">Company</h2>
      <p>Trödel Spende is an online second-hand marketplace based in Berlin where users exchange their items
        for a donation to a non-profit organisation. <a
          href="https://www.troedelspende.de" rel="noopener"
          target="_blank">www.troedelspende.de</a>
      </p>
    </v-container>
    <v-container class="text-container">
      <h2 id="brief">Brief</h2>
      <p>Our challenge was formulated with HMW (How might we), Trödel Spende asked us:

        HMW use gamification to encourage the upload of items and donations
        HMW reward the best donors on the platform
        HMW collect and display each user's trustworthiness/ reliability
      </p>
    </v-container>
    <v-container class="text-container">
      <h2 id="gettingToWork">Getting to work</h2>
      <p>We had a meeting with the stakeholders: Stéphane Piette and Daniel Reinhardt. We got access to the
        test website and site map. Stéphane and Daniel were very helpful and are committed to their project. We got the
        handover from their logos and colours design sheet. From the 5 WHYs we got the root of the challenge:
        <br><br>
        “Because people want to do good and we want to attract more people to donate”
        <br><br>
        We also discovered their Branding Attributes:
        <br><br>
        Spokesperson: Gandhi
        Animal: Guide dog
        Adjectives: Charitable, Helping, Good, Sustainable, Community.
        <br><br><br><br>

        We did the competitive analysis, getting the visual, characteristic and we also position our stakeholders.
        <br><br>
        We brainstormed all the methods we wanted to use, once we agreed I planned the project that we were updating the
        timeline according to our work.
      </p>

    </v-container>
    <v-img :src="trodelSpendeTimeline"></v-img>
    <v-container class="text-container">
      <h2 id="problemStatement">Problem Statement</h2>
      <p class="mx-16 px-16">Trödel Spende was designed to donate your unneeded stuff to an NGO.
        We have observed that Trödel Spende is not meeting the reliability
        expectations of the users and NGOs which is causing them to join less
        new users and less uploaded items to donate.
      </p>
    </v-container>
    <v-container class="text-container">
      <h2 id="surveyAndInterviewInsights">Survey and interview insights</h2>
      <p>From this point, we start an intense UX research. We brainstormed questions and tailored a survey
        that gave a stable base to work on it. We interviewed three different kinds of users: Trödel Spende user, users
        who buy/ sells in marketplaces and users involved with NGOs.
      </p>
      <ul class="ml-16">
        <li>Young people 25–34 years old</li>
        <li>66% interested in donation-based selling</li>
        <li>Likes badges 45%</li>
        <li>90% believe Reviews & Ratings build trust</li>
        <li>It feels like a double reward</li>
        <li>Not interested in a competition</li>
        <li>The option to upload more than one item</li>
        <li>Need to know that the donation truly goes to an NGO</li>
      </ul>
    </v-container>
    <v-container class="text-container">
      <h2 id="jobsToBeDone">Jobs to be Done</h2>
      <p class="text-center">When Gaby wants to get rid of his stuff, he wants to have more space, so he can enjoy his
        place.
      </p><br><br>
      <p class="text-center">
        When I find a good cause, I want to spread the word out, so other people can also use the platform.
      </p>
    </v-container>
    <v-container id="competitorsAnalysis">
      <v-row>
        <v-col cols="2"></v-col>
        <v-col cols="2">
          <v-img :src="competitorFacebook"></v-img>
        </v-col>
        <v-col cols="2">
          <v-img :src="competitorEbay"></v-img>
        </v-col>
        <v-col cols="2">
          <v-img :src="competitorNebenan"></v-img>
        </v-col>
        <v-col cols="2">
          <v-img :src="competitorHumana"></v-img>
        </v-col>
        <v-col cols="2"></v-col>
      </v-row>
      <v-row>
        <v-col cols="2"></v-col>
        <v-col cols="2">
          <v-row class="justify-center"><h2 class="ma-6">Facebook Marketplace</h2></v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/facebook/1.png"></v-img>
          </v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/facebook/2.png"></v-img>
          </v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/facebook/3.png"></v-img>
          </v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/facebook/4.png"></v-img>
          </v-row>
        </v-col>
        <v-col cols="2">
          <v-row class="justify-center"><h2 class="ma-6">Ebay Kleinanzeigen</h2></v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/ebay/1.png"></v-img>
          </v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/ebay/2.png"></v-img>
          </v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/ebay/3.png"></v-img>
          </v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/ebay/4.png"></v-img>
          </v-row>
        </v-col>
        <v-col cols="2">
          <v-row class="justify-center"><h2 class="ma-6">Nebenan</h2></v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/nebenan/1.png"></v-img>
          </v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/nebenan/2.png"></v-img>
          </v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/nebenan/3.png"></v-img>
          </v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/nebenan/4.png"></v-img>
          </v-row>
        </v-col>
        <v-col cols="2">
          <v-row class="justify-center"><h2 class="ma-6">Humana Online Shop</h2></v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/humana/1.png"></v-img>
          </v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/humana/2.png"></v-img>
          </v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/humana/3.png"></v-img>
          </v-row>
          <v-row>
            <v-img class="ma-10" src="/projects/trodelSpende/competitors/groups/humana/4.png"></v-img>
          </v-row>
        </v-col>
        <v-col cols="2"></v-col>
      </v-row>
    </v-container>
    <v-container id="painsAndGoals" class="text-container">
      <v-row>
        <h2>Pain and Goals</h2></v-row>
      <v-row><p>We organised all the insights and we defined our Pains and Goals.</p></v-row>

      <v-row>
        <v-col cols="2"></v-col>
        <v-col cols="4">
          <h4>Pain</h4>
          <ul>
            <li>Scams</li>
            <li>Many messages</li>
            <li>Missplaced messages</li>
            <li>Takes ages to sell the item</li>
            <li>Upload item function is not fast</li>
            <li>Negotiations/ Bargains/ Asking last price</li>
            <li>Take time to be answered by the messages</li>
          </ul>
        </v-col>

        <v-col cols="4">
          <h4>Goals</h4>
          <ul>
            <li>Win-win</li>
            <li>Good cause</li>
            <li>Get tax back</li>
            <li>Being recognised</li>
            <li>Near to you</li>
          </ul>
        </v-col>
        <v-col cols="2"></v-col>
      </v-row>
      <v-row>
        <v-img src="/projects/trodelSpende/painAndGoals/worstIdeas.png"></v-img>
      </v-row>
      <v-row>
        <v-col><p>Get the bitch badge by blocking everyone’s purchase</p></v-col>
        <v-col><p>You can’t decide which NGO to help, it chooses randomly</p></v-col>
        <v-col><p>As a user you can just upload one thing and then wait until all the items are sold</p></v-col>
      </v-row>
    </v-container>
    <v-container id="persona" class="text-container">
      <v-img src="/projects/trodelSpende/moscow/persona.png"></v-img>
    </v-container>
    <v-container id="moscowMethod" class="text-container">
      <v-img src="/projects/trodelSpende/moscow/moscow.png"></v-img>
    </v-container>
    <v-container id="hypothesisStatement" class="text-container">
      <v-img src="/projects/trodelSpende/moscow/problem hypothesis.png"></v-img>
    </v-container>
    <v-container id="moodBoard" class="text-container">
      <v-img src="/projects/trodelSpende/moodboard/moodboard.png"></v-img>
    </v-container>
    <v-container id="styleTile" class="text-container">
      <v-img src="/projects/trodelSpende/moodboard/style tile.png"></v-img>
    </v-container>
    <v-container id="styleGuide" class="text-container">
      <v-img src="/projects/trodelSpende/moodboard/style guide.png"></v-img>
    </v-container>
    <v-container id="siteMap" class="text-container">
      <v-img src="/projects/trodelSpende/moodboard/user flow.png"></v-img>
    </v-container>
    <v-container id="wireframesAndPrototypes" class="text-container">
      <v-row><h2>Wireframes and prototypes</h2></v-row>
      <v-img id="loFi" src="/projects/trodelSpende/moodboard/lo-fi.png"></v-img>
    </v-container>
    <v-container id="midFi" class="text-container">
      <v-img src="/projects/trodelSpende/moodboard/mid-fi.png"></v-img>
    </v-container>
    <v-container id="hiFi" class="text-container">
      <v-img src="/projects/trodelSpende/moodboard/hi-fi.png"></v-img>
    </v-container>
    <v-container id="hiFiFinalMvp" class="text-container">
      <v-row><h2>First MVP Prototype </h2></v-row>
      <v-img src="/projects/trodelSpende/mvp/mvp.png"></v-img>
      <a href="https://vimeo.com/688421400">Here you can see the full interaction.</a>
    </v-container>
    <v-container id="implementation" class="text-container">
      <h2>Implementation of our design</h2>
      <v-row>
        <v-col cols="1"></v-col>
        <v-col cols="5">
          <v-img src="/projects/trodelSpende/mvp/implementation.png"></v-img>
        </v-col>
        <v-col cols="5">
          <v-img src="/projects/trodelSpende/mvp/implementation2.png"></v-img>
        </v-col>
        <v-col cols="1"></v-col>
      </v-row>


      <p>Trödel Spende is working implementing our design, check <a href="https://troedelspende.de/">Trödel’s
        website!</a></p>
    </v-container>
    <v-container id="nextSteps" class="text-container">
      <h2>Next Steps</h2>
      <p>We are going to continue with Troedel for an internship. We keep doing Stand-ups as a UX/UI Team, and we had
        meetings to plan our next steps. <br><br><br></p>
      <ul>
        <li>Design new features</li>
        <li>Iterations on the design and usability</li>
        <li>Design the app</li>
        <li>And as always, iteration with the testing and enhancing the design.</li>
      </ul>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "CaseStudyTrodel",
  data: () => {
    return {
      trodelSpendeHeader: '/projects/trodelSpende/trodelSpendeHeader.png',
      trodelSpendeTimeline: '/projects/trodelSpende/timeline.png',
      competitorFacebook: '/projects/trodelSpende/competitors/competitorFacebook.png',
      competitorEbay: '/projects/trodelSpende/competitors/competitorEbay.png',
      competitorNebenan: '/projects/trodelSpende/competitors/competitorNebenan.png',
      competitorHumana: '/projects/trodelSpende/competitors/competitorHumana.png',
    }
  }
}
</script>

<style scoped>

img {
  width: 100vh;
}

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

/*.image-height {*/
/*  max-height: 714px;*/
/*  max-width: 300px;*/
/*}*/

.text-container {
  padding-left: 20%;
  padding-right: 20%;
}
</style>
