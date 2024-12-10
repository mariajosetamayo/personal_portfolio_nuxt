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
          :src="require('@/assets/fitness_tribe/fitnesstribe_persona.png')"
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

    <!-- Research Section -->
    <v-row align="start" justify="start">
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
          :src="require('@/assets/fitness_tribe/mapmyrun_screenshot.png')"
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
          :src="require('@/assets/fitness_tribe/strava_screenshot.png')"
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
    <v-row align="start" justify="start" class="color-section">
      <!-- Define Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Define</h1>
        <br />
        <p>
          The conducted research was used to ideate a solution for the new
          feature.
        </p>

        <h2 class="sub-title">Key Characteristics</h2>
        <ul>
          <li>
            New functionality allows people to join fitness challenges so that
            they can have a common goal with friends, family members, and
            members of the community.
          </li>
          <li>
            New functionality allows users to engage through the social media
            functionality of a feed and private messaging so that people can
            communicate their achievements, progress, and any other information
            to friends, family, and members of the community.
          </li>
          <li>
            The app suggests users challenges that they can join based on their
            objectives after answering a short questionnaire.
          </li>
        </ul>
        <br />
        <h2 class="sub-title">User Flows</h2>
        <br />
        <h3>The Process of Joining a Challenge</h3>
      </v-col>
      <ExpandableImage
        :imageSrc="require('@/assets/fitness_tribe/flow_chart_ft.png')"
      ></ExpandableImage>
      <br />
      <h3>The Process of Adding Friends</h3>
      <br />
      <ExpandableImage
        :imageSrc="require('@/assets/fitness_tribe/flow_chart_2_ft.png')"
      ></ExpandableImage>
      <br />
      <h3>The Process of Sending a Message</h3>
      <br />
      <ExpandableImage
        :imageSrc="require('@/assets/fitness_tribe/flow_chart_ft_3.png')"
      ></ExpandableImage>
    </v-row>
    <v-row align="start" justify="start">
      <!-- Design Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Design</h1>
        <br />
        <h2 class="sub-title">Low Fidelity Wireframes</h2>
        <br />
        <p>
          After defining the user flows and the key features that needed to be
          included in the app, I created low fidelity wireframes. I Used these
          for an initial round of moderated user testing with 5 users. All user
          testing sessions were conducted by Zoom.
        </p>
      </v-col>
      <ExpandableImage
        :imageSrc="require('@/assets/fitness_tribe/wireframes_ft.png')"
      ></ExpandableImage>
      <v-col cols="12" md="10">
        <h2 class="sub-title">Key Testing Insights</h2>
        <br />
        <ul>
          <li>
            Users got confused with the navigation to send messages. Users kept
            going to the message icon located at the footer to send all types of
            messages.
          </li>
          <li>
            Users found it confusing having the chat next to the private
            messages to the group on the quest’s page.
          </li>
          <li>
            Users had difficulty differentiating between the icons to add a
            quest and to add a friend. Even though they are familiar with the
            icons, the unfamiliarity with the app made them get both of these
            icons confused.
          </li>
          <li>
            Users found the term quest confusing. Some suggested using the term
            “challenges” instead.
          </li>
          <li>
            Users mentioned that they would not be likely to join a challenge
            that was not created by a professional.
          </li>
        </ul>
      </v-col>
    </v-row>
    <!-- Brand Platform Section-->
    <v-row class="py-10">
      <v-col cols="12">
        <h1>Brand Platform</h1>
        <br />
        <h2 class="sub-title">Logo</h2>
        <br />
        <p>
          The logo is a combination of the initials of FitnessTribe (F and T).
          It is made out of circles to convey the concept of unity since the
          app’s main goal is to connect friends and family through fitness.
        </p>
      </v-col>
      <v-col cols="12" md="6">
        <v-img
          :src="require('@/assets/fitness_tribe/logo_ft_measures.png')"
          alt="Logo Fitness Tribe"
          contain
          max-height="300"
        ></v-img>
      </v-col>
      <v-col cols="12" md="6">
        <v-img
          :src="require('@/assets/fitness_tribe/logo_ft_measures_2.png')"
          alt="Logo Fitness Tribe"
          contain
          max-height="300"
        ></v-img>
      </v-col>
      <v-col cols="12">
        <h2 class="sub-title">Color Palette</h2>
        <br />
        <p>
          The color palette incorporates a mix of green, grey, and black with
          orange accents. The combination of these colors is meant to convey
          inclusiveness, growth, and energy.
        </p>
      </v-col>
      <ExpandableImage
        :imageSrc="require('@/assets/fitness_tribe/color_palette_ft.png')"
      ></ExpandableImage>
    </v-row>
    <!-- High Fidelity Designs -->
    <v-row class="py-10">
      <v-col cols="12">
        <h1>High Fidelity Designs</h1>
        <br />
        <p>
          Using the wireframes and the findings of the initial round of user
          testing, I created high fidelity designs. I also incorporated the
          color palette, the logo and chose to use Poppins as the main font for
          my designs.
        </p>
      </v-col>
      <div>
        <ImageGrid
          :images="[
            {
              src: require('@/assets/fitness_tribe/get-started-page.png'),
              alt: 'Screen 1',
            },
            {
              src: require('@/assets/fitness_tribe/questionnaire-1.png'),
              alt: 'Screen 2',
            },
            {
              src: require('@/assets/fitness_tribe/suggestions.png'),
              alt: 'Screen 3',
            },
            {
              src: require('@/assets/fitness_tribe/suggestions-yoga.png'),
              alt: 'Screen 4',
            },
            {
              src: require('@/assets/fitness_tribe/profile.png'),
              alt: 'Screen 4',
            },
            {
              src: require('@/assets/fitness_tribe/participants.png'),
              alt: 'Screen 4',
            },
            {
              src: require('@/assets/fitness_tribe/feed.png'),
              alt: 'Screen 4',
            },
            {
              src: require('@/assets/fitness_tribe/friend-profile.png'),
              alt: 'Screen 4',
            },
            {
              src: require('@/assets/fitness_tribe/chat.png'),
              alt: 'Screen 4',
            },
            {
              src: require('@/assets/fitness_tribe/congratulations.png'),
              alt: 'Screen 4',
            },
          ]"
        />
      </div>
    </v-row>
    <!-- Testing -->
    <v-row class="py-10">
      <v-col cols="12">
        <h1>Tests</h1>
        <br />
        <p>
          I conducted a moderated usability test with 5 subjects. I showed each
          subject the prototype while I gave them a series of tasks to complete.
        </p>
        <p>
          I recruited participants in Boulder, Colorado and Mexico City. All of
          us were 20-37 years old and had moderate to high physical activity
          levels. We were mostly middle-income sport enthusiasts who spent an
          average of 30-50 USD monthly on phone and web applications. We had all
          used a fitness app on our mobile phones.
        </p>
        <h2 class="sub-title">Key Testing Insights</h2>
        <br />
        <ul>
          <li>
            No back arrow to go to the previous page. The only current
            navigation is located in the footer and causes frustration in users.
          </li>
          <li>
            Users would like to have more direct access to see their friends and
            see what challenges they are currently completing.
          </li>
          <li>
            A majority of the users mentioned that they would like to search for
            people who are using the app and not only their contacts.
          </li>
          <li>
            Several users mentioned that they would like to have an option to
            give kudos instead of liking a post. They mentioned the kudos icon
            in Strava as a reference.
          </li>
          <li>
            Users mentioned that they would like to have gamification features.
            Some suggested that it would be good to use medals or a point system
            for the challenges.
          </li>
        </ul>
        <br />
        <h2 class="sub-title">Changes to the Design</h2>
        <br />
        <p>
          After testing, I iterated on the designs and incorporated the main
          findings. I also updated the main prototype.
        </p>
        <br />
        <div class="justify-center">
          <ExpandableImage
            :imageSrc="require('@/assets/fitness_tribe/change_design_ft_1.png')"
          ></ExpandableImage>
          <ExpandableImage
            :imageSrc="require('@/assets/fitness_tribe/change_design_ft_2.png')"
          ></ExpandableImage>
          <ExpandableImage
            :imageSrc="require('@/assets/fitness_tribe/change_design_ft_3.png')"
          ></ExpandableImage>
        </div>
      </v-col>
    </v-row>
    <v-row align="start" justify="start" class="color-section end">
      <!-- Improvements Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Future Improvements</h1>
        <br />
        <p>
          Due to time restrictions, certain improvements remain pending for
          future versions of the design.
        </p>

        <h2 class="sub-title">Key Improvements</h2>
        <ul>
          <li>
            User’s feedback is needed for the newly added features to add
            friends.
          </li>
          <li>
            The gamification features need to be further developed and tested.
            More research on successful gamification on existing fitness apps
            could be helpful. Furthermore, interviews with users would be
            valuable to further design the point system and badges.
          </li>
          <li>
            Adding challenges needs to be further researched. This is because
            users mentioned during testing sessions that they would not trust
            and necessarily be motivated by a challenge that was not added by a
            professional. After research is conducted, a feature to add
            challenges needs to be designed.
          </li>
        </ul>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import FitnessTribe from '@/components/FitnessTribe.vue'
import ExpandableImage from '@/components/ExpandableImage.vue'
import ImageGrid from '@/components/ImageGrid.vue'

export default {}
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

.color-section {
  background-color: #f9fcfb;
}

.end {
  margin-bottom: 50px;
}
@media (max-width: 768px) {
  .dark-card {
    background-color: #0b1624;
    margin-top: 0px;
  }
}
</style>
