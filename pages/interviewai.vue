<template>
  <v-container fluid>
    <InterviewAi :showButton="false"></InterviewAi>
    <!-- Project Overview Section -->
    <v-row align="start" justify="start">
      <!-- Project Overview Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Project Overview</h1>
        <br />
        <p>
          Interview AI streamlines the interview process for companies by
          generating relevant and effective questions based on job category and
          position. Its features enable professionals to manage interviews
          fairly for all candidates.
        </p>

        <h2 class="sub-title">Problem</h2>
        <p>
          Interview AI launched a live version of their product at the beginning
          of 2023. Although the product had some success attracting users, it
          was registering low retention rates. This is mainly seen through two
          factors:
        </p>
        <ul>
          <li>
            Users tried the product but do not sign up
          </li>
          <li>
            There was a significant number of orphan interviews
          </li>
        </ul>
        <br />
        <p>These issues led to the following question:</p>
        <h4>“How might we increase user retention rates?”</h4>
        <br />

        <h2 class="sub-title">Solution</h2>
        <p>
          After some analysis, we determined that there were many factors that
          could be causing user retention issues. After conducting secondary
          research, we decided to focus on two possible culprits: the landing
          page and the user flow. Based on the insights from our primary
          research, we decided that we needed to work on the following:
        </p>
        <ol>
          <li>Improving the feel and look of the landing page</li>
          <li>
            Conveying more and clearer information and guidance throughout the
            product to users
          </li>
          <li>
            Making changes to the user flow so that users could enter a job
            candidate’s information, create the interview script assisted with
            AI to generate questions, save the interview script, and conduct the
            interview.
          </li>
        </ol>
      </v-col>
    </v-row>

    <!-- Research Section -->
    <v-row class="py-10">
      <v-col cols="12">
        <h1>Research</h1>
      </v-col>
      <v-col cols="12" md="10">
        <h2>Methodology</h2>
        <p>
          The project lasted 5 weeks with weekly meetings with the client. The
          team consisted of 3 UX/UI designers. I acted as the client contact and
          team coordinator.
        </p>
        <p>
          Our research involved a literature review on HR software trends and AI
          usage in the industry. We also conducted competitor analysis to
          identify Interview AI's unique features.
        </p>
        <p>
          We conducted 2 rounds of usability testing: one with the live product
          and another with the initial design prototype.
        </p>
        <p>The subsequent sections delve deeper into each research phase.</p>
      </v-col>
      <v-col cols="12" md="10">
        <h2 class="sub-title">Secondary Research</h2>
        <p>
          In our initial research, we explored HR software trends and AI usage
          in the industry. Key findings include:
        </p>
        <ul>
          <li>
            There is a growing prevalence of AI-powered recruitment tools and
            chatbots, streamlining the hiring process and reducing time-to-hire.
          </li>
          <li>
            AI is used for job recommendations, candidate matching, job
            description suggestions, automated candidate screening, and
            engagement scoring.
          </li>
          <li>
            AI shows promise in removing bias from job descriptions, using
            language replacement tools.
          </li>
          <li>
            Robotic process automation (RPA) automates manual, repetitive tasks
            on a large scale.
          </li>
          <li>
            Skill-based assessments and diversity and inclusion are gaining
            importance.
          </li>
        </ul>
        <br />
        <p>
          Conclusions from this research phase:
        </p>
        <ul>
          <li>
            Interview AI operates in a competitive industry, requiring clear
            communication of its advantages over competitors.
          </li>
          <li>
            Recommended platform enhancements: candidate scoring, resume-based
            screening questions.
          </li>
          <li>
            Prioritize incorporating as many RPAs as possible to the platform.
          </li>
          <li>
            Emphasize Interview AI's mission to ensure fair interviews.
          </li>
        </ul>
        <br />
        <h2 class="sub-title">Competitor Analysis</h2>
        <br />
        <ExpandableImage
          :imageSrc="require('@/assets/interview_ai/competitor_analysis.png')"
        ></ExpandableImage>
      </v-col>
      <!-- Define Section -->
      <v-col cols="12" md="10">
        <h2 class="section-title">Primary Research</h2>
        <br />
        <p>
          As the initial step, we performed moderated usability testing on the
          live product, involving 5 remote interviews conducted via Zoom.
          Recordings and transcriptions were made for all interviews. We
          identified patterns through an affinity map, and we created a user
          journey map to enhance our understanding of user experience.
          Additionally, we created a prioritization matrix to determine task
          priorities, considering development time and user requirements. As a
          Front-End Engineer, I played a key role in determining development
          time and task prioritization.
        </p>
        <br />
        <h2 class="section-title">User Journey Map</h2>
        <br />
        <ExpandableImage
          :imageSrc="require('@/assets/interview_ai/user_journey_map.png')"
        ></ExpandableImage>
      </v-col>
    </v-row>
    <h2 class="sub-title">Identified Themes and Prioritization</h2>

    <v-row class="py-10" justify="center" align="stretch">
      <!-- Text Column -->
      <v-col cols="12" md="6" class="d-flex flex-column">
        <v-card flat>
          <v-card-title>
            <h4><b>Theme 1 - Insufficient Information</b></h4>
          </v-card-title>
          <v-card-text>
            <p><b>An observed pattern was that all users:</b></p>
            <ol>
              <li>Were not sure about what the product actually does</li>
              <li>How it could benefit them</li>
              <li>
                Found that the information provided on the landing page was
                misleading
              </li>
            </ol>
            <br />
            <blockquote>
              “Oh, I didn’t realize that I had to conduct the interview. I
              understood that an AI bot would interview the candidate in
              real-time.”
            </blockquote>
            <br />
            <p><b>Suggestions:</b></p>
            <ul>
              <li>The copy on the landing page</li>
              <li>
                Adding information about the benefits of signing up and using
                the product
              </li>
              <li>
                Adding information that can support user navigation and user
                onboarding
              </li>
            </ul>
          </v-card-text>
        </v-card>
      </v-col>

      <!-- Graph Column -->
      <v-col cols="12" md="6" class="d-flex justify-center align-center">
        <v-card flat>
          <v-card-text class="d-flex justify-center align-center">
            <v-img
              :src="require('@/assets/interview_ai/theme-1-graph.png')"
              alt="Graph"
              contain
              class="graph-image"
            ></v-img>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
    <v-row class="py-10" justify="center" align="stretch">
      <!-- Text Column -->
      <v-col cols="12" md="6" class="d-flex flex-column">
        <v-card flat>
          <v-card-title>
            <h4><b>Theme 2 - UI Design</b></h4>
          </v-card-title>
          <v-card-text>
            <p>
              <b>
                An observed pattern was that all users found it difficult to
                focus on the tasks and crucial details because:
              </b>
            </p>
            <ol>
              <li>
                Their attention was drawn to secondary elements such as the
                delete question button on the interview page.
              </li>
              <li>There was too much information to read at one time.</li>
              <li>
                Icons are located on unexpected and unintuitive places.
              </li>
            </ol>
            <br />
            <blockquote>
              “I’m finding it hard to read the question because the delete
              question button keeps catching my attention.”
            </blockquote>
            <br />
            <p><b>Suggestions:</b></p>
            <ul>
              <li>
                Changing the visual hierarchy of headers, text, and components.
              </li>
              <li>
                Changing the page layout where relevant.
              </li>
              <li>
                Correcting spacing.
              </li>
              <li>
                Adhere to using icons and UI patterns that users are familiar
                with.
              </li>
            </ul>
          </v-card-text>
        </v-card>
      </v-col>

      <!-- Graph Column -->
      <v-col cols="12" md="6" class="d-flex justify-center align-center">
        <v-card flat>
          <v-card-text class="d-flex justify-center align-center">
            <v-img
              :src="require('@/assets/interview_ai/theme-2-graph.png')"
              alt="Graph"
              contain
              class="graph-image"
            ></v-img>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
    <v-row class="py-10" justify="center" align="stretch">
      <!-- Text Column -->
      <v-col cols="12" md="6" class="d-flex flex-column">
        <v-card flat>
          <v-card-title>
            <h4><b>Theme 3 - Lack of User Control</b></h4>
          </v-card-title>
          <v-card-text>
            <p>
              <b>
                An observed pattern was that all users got frustrated because
                they could not:
              </b>
            </p>
            <ol>
              <li>
                Customize the interview question script
              </li>
              <li>
                Add their own questions that are relevant to their company’s
                specific needs.
              </li>
              <li>
                Add more candidate information.
              </li>
            </ol>
            <br />
            <blockquote>
              “I’am really surprised that I cannot add my own questions. What if
              my team has something specific that we would like to ask?”
            </blockquote>
            <br />
            <p><b>Suggestions:</b></p>
            <ul>
              <li>
                Adding functionality that allows users to add their own
                questions and customize the interview script.
              </li>
              <li>
                Adding functionality to add more candidate information, for
                example allowing users to upload the candidate’s resume.
              </li>
              <li>
                Adding more personalization/customization where relevant and
                possible.
              </li>
            </ul>
          </v-card-text>
        </v-card>
      </v-col>

      <!-- Graph Column -->
      <v-col cols="12" md="6" class="d-flex justify-center align-center">
        <v-card flat>
          <v-card-text class="d-flex justify-center align-center">
            <v-img
              :src="require('@/assets/interview_ai/theme-3-graph.png')"
              alt="Graph"
              contain
              class="graph-image"
            ></v-img>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>

    <v-row class="py-10" justify="center" align="stretch">
      <!-- Text Column -->
      <v-col cols="12" md="6" class="d-flex flex-column">
        <v-card flat>
          <v-card-title>
            <h4><b>Theme 4 - Interview Flow</b></h4>
          </v-card-title>
          <v-card-text>
            <p>
              <b>
                An observed pattern was that users need to prepare an interview
                script prior to the interview because:
              </b>
            </p>
            <ol>
              <li>
                They need to choose the questions with their team and agree on
                which ones to ask.
              </li>
              <li>
                They need HR to approve the interview questions in some
                instances.
              </li>
            </ol>
            <br />
            <blockquote>
              “I wouldn’t use this product unless I could choose the interview
              questions ahead. The AI would be very handy to prepare my
              interview though.”
            </blockquote>
            <br />
            <p><b>Suggestions:</b></p>
            <ul>
              <li>
                Adding a feature that allows users to prepare their interview
                script prior to the interview.
              </li>
              <li>
                Using the current AI functionality to allow users to generate
                questions for their interview script prior to the interview.
              </li>
            </ul>
          </v-card-text>
        </v-card>
      </v-col>

      <!-- Graph Column -->
      <v-col cols="12" md="6" class="d-flex justify-center align-center">
        <v-card flat>
          <v-card-text class="d-flex justify-center align-center">
            <v-img
              :src="require('@/assets/interview_ai/theme-4-graph.png')"
              alt="Graph"
              contain
              class="graph-image"
            ></v-img>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>

    <v-row class="py-10" justify="center" align="stretch">
      <!-- Text Column -->
      <v-col cols="12" md="6" class="d-flex flex-column">
        <v-card flat>
          <v-card-title>
            <h4><b>Theme 5 - Functionality</b></h4>
          </v-card-title>
          <v-card-text>
            <p>
              <b>
                An observed pattern was that users would like to see more
                features that are included in most competitor products such as:
              </b>
            </p>
            <ol>
              <li>
                Recording and transcription of the interview.
              </li>
              <li>
                Ability to export the interview.
              </li>
              <li>
                ATS integration.
              </li>
            </ol>
            <br />
            <blockquote>
              “Why should I use InterviewAI for my notes if I can just record
              the meeting and use ChatGPT to transcribe it?”
            </blockquote>
            <br />
            <p><b>Suggestions:</b></p>
            <ul>
              <li>
                Adding a feature that allows users to record the interview.
              </li>
              <li>
                Adding a feature that transcribes the interview for the user.
              </li>
              <li>
                Adding functionality to export and/or share the interview file.
              </li>
              <li>
                Adding ATS integration.
              </li>
            </ul>
          </v-card-text>
        </v-card>
      </v-col>

      <!-- Graph Column -->
      <v-col cols="12" md="6" class="d-flex justify-center align-center">
        <v-card flat>
          <v-card-text class="d-flex justify-center align-center">
            <v-img
              :src="require('@/assets/interview_ai/theme-3-graph.png')"
              alt="Graph"
              contain
              class="graph-image"
            ></v-img>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
    <v-row align="start" justify="start" class="color-background">
      <!-- Define Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Define</h1>
        <br />
        <p>
          The data obtained from the usability testing was used to determine the
          user flow for the product. The user flow had to be adapted to certain
          technical constraints due to limited funding and a single developer
          working on this product. Therefore, certain aspects of the user flow
          were compromised, such as not giving the ability to users to save
          interview scripts by position and saving candidate’s data. However,
          improvements were made by enhancing product information and providing
          user guidance. The objective was to minimize user confusion and
          frustration.
        </p>

        <h2 class="sub-title">User Flow</h2>
        <br />
        <ExpandableImage
          :imageSrc="require('@/assets/interview_ai/user-flow.png')"
        ></ExpandableImage>
      </v-col>
    </v-row>
    <v-row align="start" justify="start">
      <!-- Design Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Design</h1>
        <br />
        <p>
          After identifying the user needs and agreeing with a user flow, we
          started creating the designs. Our designs needed to cover the
          following:
        </p>
        <ol>
          <li>
            Re-designing the landing page with more information about the
            product
          </li>
          <li>
            Adding a Dashboard
          </li>
          <li>
            Adding progressive disclosure in the user flow and more guidance for
            the user
          </li>
          <li>
            Adding an interview script editor page
          </li>
          <li>
            Re-designing the page for conducting an interview
          </li>
          <li>
            Re-designing the interview summary page
          </li>
          <li>
            Adding a page to consult past interviews and saved scripts
          </li>
        </ol>
        <br />

        <h2 class="sub-title">Sketches</h2>
        <br />
        <p>
          By creating sketches, we were able to identify the following aspects:
        </p>
        <ol>
          <li>
            We determined the sections that needed to be included on the landing
            page
          </li>
          <li>
            We decided to use a stepper to include progressive disclosure of
            information in order to avoid cognitive overload and guide the user
          </li>
          <li>
            The dashboard would include lists of recently created interview
            scripts and recently conducted interviews
          </li>
        </ol>
      </v-col>
    </v-row>
    <v-row justify="center" align="center" class="py-10">
      <!-- First Row -->
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/sketch-1.png')"
          alt="Sketch 1"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/sketch-2.png')"
          alt="Sketch 2"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/sketch-3.png')"
          alt="Sketch 3"
          class="sketch-image"
        ></v-img>
      </v-col>
      <!-- Second Row -->
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/sketch-4.png')"
          alt="Sketch 4"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/sketch-5.png')"
          alt="Sketch 5"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/sketch-6.png')"
          alt="Sketch 6"
          class="sketch-image"
        ></v-img>
      </v-col>
    </v-row>
    <v-row align="start" justify="start">
      <!-- Design Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Wireframes</h1>
        <br />
        <p>
          During the wire-framing process, we explored the following aspects:
        </p>
        <ol>
          <li>
            The information to be included on the landing page
          </li>
          <li>
            The general layout of the dashboard and the navigation drawer, with
            the decision to make the navigation drawer collapsible
          </li>
          <li>
            The layout and steps to be included in the stepper
          </li>
          <li>
            The layout and functionality required for the interview conducting
            page
          </li>
          <li>
            The layout and information to be included in the interview summary
            page
          </li>
        </ol>
      </v-col>
    </v-row>
    <v-row justify="center" align="center" class="py-10">
      <!-- First Row -->
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/landing_page.png')"
          alt="Sketch 1"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/dashboard.png')"
          alt="Sketch 2"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/create_interview_page.png')"
          alt="Sketch 3"
          class="sketch-image"
        ></v-img>
      </v-col>
      <!-- Second Row -->
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/create_interview_script.png')"
          alt="Sketch 4"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/create_interview_script_2.png')"
          alt="Sketch 5"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/create_interview_script_3.png')"
          alt="Sketch 6"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/interviewing_1.png')"
          alt="Sketch 6"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/interviewing_2.png')"
          alt="Sketch 6"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="4">
        <v-img
          :src="require('@/assets/interview_ai/evaluation.png')"
          alt="Sketch 6"
          class="sketch-image"
        ></v-img>
      </v-col>
    </v-row>
    <v-row align="start" justify="start">
      <!-- Design Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Visual Guidelines</h1>
        <br />
        <p>
          Interview AI did not have clear branding guidelines. However, during
          the initial meeting, the client expressed their desire to retain their
          current logo. After subsequent discussions, we identified four key
          brand attributes that needed to be reflected in the design:
        </p>
        <ul>
          <li>
            Efficient
          </li>
          <li>
            Trustworthy
          </li>
          <li>
            Helpful
          </li>
          <li>
            Fair
          </li>
        </ul>
        <br />
        <p>
          These attributes served as inspiration for our choice of color palette
          and typography. The color palette primarily consists of monochromatic
          shades of blue and gray. We specifically selected blue due to its
          commonly associated traits of trust, intelligence, and efficiency.
        </p>
        <v-img
          :src="require('@/assets/interview_ai/colors.png')"
          alt="colors"
        ></v-img>
        <p>
          For the typography, we chose two fonts that are rounded to convey the
          attribute of fairness. The weights and sizes mostly follow Golden
          Ratio proportions with the exception of typefaces used for the landing
          page.
        </p>
        <v-img
          :src="require('@/assets/interview_ai/typography.png')"
          alt="typography"
        ></v-img>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import InterviewAi from '@/components/InterviewAi.vue'
import ExpandableImage from '@/components/ExpandableImage.vue'
import ImageGrid from '@/components/ImageGrid.vue'
import Button from '@/components/Button.vue'

export default {
  components: { ExpandableImage },
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

.quote {
  font-style: italic;
}

.dark-card {
  background-color: #2d50cd;
  /* margin-top: 150px; */
}

.dark-card-app {
  background-color: #0b1624;
}

.end {
  margin-bottom: 50px;
}

blockquote {
  font-style: italic;
  color: #555;
  border-left: 4px solid #ccc;
  padding-left: 10px;
  margin-left: 0;
}

.graph-image {
  width: 100%;
  max-width: 500px;
  height: auto;
  /* border: 1px solid #ddd; */
  border-radius: 8px;
  padding: 8px;
  background-color: #fff;
}

.color-background {
  background-color: #fcfcff;
  padding-top: 30px;
}

.sketch-image {
  width: 100%;
  height: 100%;
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 8px;
  background-color: #fff;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
@media (max-width: 768px) {
  .dark-card {
    /* background-color: #0b1624; */
    margin-top: 0px;
  }

  .graph-image {
    max-width: 100%; /* Make sure it doesn't exceed the screen width */
  }
}
</style>
