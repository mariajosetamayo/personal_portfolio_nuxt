<template>
  <v-container fluid>
    <FitnessTribe :showButton="false"></FitnessTribe>
    <!-- Project Overview Section -->
    <v-row align="start" justify="start">
      <!-- Project Overview Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Project Overview</h1>
        <br />
        <p>
          FitnessTribe is an app available for IOS and Android where friends and
          family can share health and fitness goals.
        </p>

        <h2 class="sub-title">Problem</h2>
        <p>
          FitnessTribe wanted to find a way to retain more users. Early research
          indicated that users were not using the app since it didn’t have an
          integrated messaging feature. Therefore, the company would like to add
          this feature to the product. The messaging feature should have the
          goals of:
        </p>
        <ul>
          <li>
            Providing the opportunity for users to message each other with
            health and fitness goals/achievements.
          </li>
          <li>
            Creating an integrated messaging experience throughout the product
            to drive engagement and repeat usage.
          </li>
        </ul>
        <br />
        <h2 class="sub-title">Solution</h2>
        <p>
          To increase user engagement, I came up with the solution of allowing
          users to create and join fitness challenges. Apart from this, I also
          designed a solution where people can message each other through
          private messages/chat or comment on people’s posts.
        </p>
      </v-col>
    </v-row>

    <!-- Research Section -->
    <v-row class="py-10">
      <v-col cols="12">
        <h1>Research & Insights</h1>
      </v-col>
      <v-col cols="12" md="6">
        <v-img
          :src="require('@/assets/fitnesstribe_persona.png')"
          alt="Research"
          contain
          max-height="600"
        ></v-img>
      </v-col>

      <v-col cols="12" md="6">
        <v-card class="dark-card">
          <v-card-title class="white--text">
            <h2 class="highlight">Characteristics</h2>
          </v-card-title>
          <v-card-text class="white--text">
            <p>
              Although FitnessTribe can be used by people of any age, the main
              target audience has the following characteristics:
            </p>
            <ul>
              <li>18 - 34 years old</li>
              <li>
                Very tech-savvy — they are on their phones for several hours a
                day
              </li>
              <li>Very budget-conscious</li>
              <li>
                Messaging and communicating with friends and family is a very
                important part of their daily lives
              </li>
            </ul>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>

    <!-- Design Process Section -->
    <v-row align="start" justify="start">
      <!-- Project Overview Section -->
      <v-col cols="12" md="10">
        <h2 class="sub-title">Secondary Research</h2>
        <p>
          As a first step, I conducted a literature review with the purpose of
          finding what aspect increase user’s engagement in fitness apps. The
          key insights of this research included:
        </p>
        <ul>
          <li>
            The social feature should have a strong reciprocation element.
          </li>
          <li>
            The feature should appeal to a harmonious passion.
          </li>
          <li>
            The feature should make the users feel like they are creating a
            community of like-minded exercisers.
          </li>
          <li>
            It is important to give users the ability to give feedback and show
            appreciation.
          </li>
          <li>
            Users should work towards a common goal.
          </li>
          <li>
            It is important to give control to the user at all times.
          </li>
          <li>
            It is important not to emphasize competition.
          </li>
          <li>
            Avoid making users feel like they need to prove themselves through
            the feature.
          </li>
        </ul>
        <br />
        <h2 class="sub-title">Analysis of Existing Products</h2>
        <p>
          To get an idea of what other products currently offer, I analyzed
          characteristics of 2 different popular apps: MapMyRun and Strava. I
          specifically focused on the app’s functionality to engage with other
          users, send messages and other ways to communicate.
        </p>
        <h2 class="sub-title">MapMyRun</h2>
        <p>
          MapMyRun has 10M+ downloads on the Google Play Store. It has been
          acquired by Under Armour. The app tracks your route, distance, and
          more in real-time using GPS. It also allows you to connect with
          friends. In this app, I looked at how to add friends.
        </p>
      </v-col>
      <v-col cols="12" md="6">
        <v-img
          :src="require('@/assets/mapmyrun_screenshot.png')"
          alt="Research"
          contain
          max-height="550"
        ></v-img>
      </v-col>

      <v-col cols="12" md="6">
        <v-card class="dark-card-app">
          <v-card-title class="white--text">
            <h3 class="highlight">Likes</h3>
          </v-card-title>
          <v-card-text class="white--text">
            <ul>
              <li>It has the functionality to add friends</li>
              <li>
                You can see different social feeds: personal, community, and
                your own posts
              </li>
              <li>You can comment and like posts</li>
              <li>
                You can join fitness challenges and add challenges
              </li>
            </ul>
          </v-card-text>
          <v-card-title class="white--text">
            <h3 class="highlight">Dislikes</h3>
          </v-card-title>
          <v-card-text class="white--text">
            <ul>
              <li>
                Finding friends is not easy. The app does not sync with your
                contacts
              </li>
              <li>
                There is a limited variety of challenges
              </li>
              <li>There are no recommendations for where to start</li>
            </ul>
          </v-card-text>
          <v-card-title class="white--text">
            <h3 class="highlight">Action Items</h3>
          </v-card-title>
          <v-card-text class="white--text">
            <ul>
              <li>
                Add a variety of challenges to increase engagement
              </li>
              <li>
                Add a social feed
              </li>
              <li>Give users more guidance on where to start</li>
            </ul>
          </v-card-text>
        </v-card>
      </v-col>
      <v-col cols="12" md="10">
        <h2 class="sub-title">Strava</h2>
        <p>
          Strava is a popular app to track fitness activities such as running,
          hiking, and biking. It has 50M+ downloads in the Google Play Store. It
          offers many attractive features to interact with other users.
        </p>
      </v-col>
      <v-col cols="12" md="6">
        <v-img
          :src="require('@/assets/strava_screenshot.png')"
          alt="Research"
          contain
          max-height="600"
        ></v-img>
      </v-col>

      <v-col cols="12" md="6">
        <v-card class="dark-card-app">
          <v-card-title class="white--text">
            <h3 class="highlight">Likes</h3>
          </v-card-title>
          <v-card-text class="white--text">
            <ul>
              <li>It has the functionality to add friends</li>
              <li>
                You can see a social feed for you're friend’s activities and
                give them kudos. Since it is more popular, it is easier to find
                your friends
              </li>
              <li>You can comment on posts</li>
              <li>
                You can join a variety fitness challenges
              </li>
            </ul>
          </v-card-text>
          <v-card-title class="white--text">
            <h3 class="highlight">Dislikes</h3>
          </v-card-title>
          <v-card-text class="white--text">
            <ul>
              <li>
                Challenges and clubs are not all free
              </li>
              <li>
                You cannot send direct messages to other users
              </li>
              <li>
                There are no recommendations for where to start with challenges
              </li>
            </ul>
          </v-card-text>
          <v-card-title class="white--text">
            <h3 class="highlight">Action Items</h3>
          </v-card-title>
          <v-card-text class="white--text">
            <ul>
              <li>
                Add a variety of free challenges to increase engagement
              </li>
              <li>
                Add a social feed and a way to send direct messages
              </li>
              <li>
                Give users more guidance on where to start with challenges
              </li>
            </ul>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>

    <!-- UI Showcase -->
    <v-row class="py-10">
      <v-col cols="12">
        <h2>UI Designs</h2>
      </v-col>
      <v-col cols="12" md="4" v-for="(image, index) in uiDesigns" :key="index">
        <v-img :src="image" alt="UI Design" contain></v-img>
      </v-col>
    </v-row>

    <!-- Future Improvements -->
    <v-row class="py-10">
      <v-col cols="12">
        <h2>Future Improvements</h2>
        <p>
          Final thoughts, future steps for the app, and closing remarks.
        </p>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import FitnessTribe from '@/components/FitnessTribe.vue'

export default {
  data() {
    return {
      uiDesigns: [
        // require('@/assets/ui1.png'),
        // require('@/assets/ui2.png'),
        // require('@/assets/ui3.png'),
      ],
    }
  },
}
</script>

<style scoped>
h1,
h2 {
  font-weight: bold;
}

p {
  line-height: 1.6;
}
.logo {
  margin-bottom: 30px;
}
.hero-row {
  width: 100%;
  margin: 0;
  padding: 0;
}

.text-section {
  text-align: left;
}

.hero-title {
  font-size: 3rem;
  font-weight: bold;
  margin-top: 1rem;
}

.highlight {
  color: #00ccb2; /* Highlight color */
}

.dark-card {
  background-color: #0b1624;
  margin-top: 150px;
}

.dark-card-app {
  background-color: #0b1624;
}
@media (max-width: 768px) {
  .dark-card {
    background-color: #0b1624;
    margin-top: 0px;
  }
}
</style>
