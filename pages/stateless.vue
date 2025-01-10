<template>
  <v-container fluid>
    <Stateless :showButton="false"></Stateless>
    <!-- Project Overview Section -->
    <v-row align="start" justify="start">
      <!-- Project Overview Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Product Description</h1>
        <br />
        <p>
          Stateless is a software which has a patented architecture where state
          and processing are decoupled from network functions, then broken down
          into micro-network functions to enable simple, scalable and dynamic
          networking.
        </p>

        <h2 class="sub-title">Problem</h2>
        <p>
          As the third engineering hired at Stateless, I spearheaded the design
          and implementation of the UI for the MVP, pivotal in securing seed
          funding. My role involved visually articulating our revolutionary
          technology, which seamlessly decouples state from network functions
          while minimizing latency. Despite the complexity, I effectively
          showcased our innovation within a stringent 4-month timeframe, crucial
          in conveying our breakthrough solution to potential investors.
        </p>

        <br />

        <h2 class="sub-title">Solution</h2>
        <p>
          With just 4 months to design and code a UI interfacing with a complex
          backend at Stateless, I strategized time management and collaborated
          closely with the team under the guidance of our engineering manager.
          Initially unfamiliar with networking, I leveraged this fresh
          perspective to streamline understanding and communication. After
          extensive research, I designed a minimalist UI focused on essential
          MVP functionalities:
        </p>
        <ul>
          <li>Implemented user controls for network traffic management.</li>
          <li>
            Visualized backend load balancing and network latency dynamics.
          </li>
          <li>
            Integrated real-time logs for user system visibility.
          </li>
        </ul>
        <p>
          This approach ensured clarity and usability, crucial for our MVP’s
          success.
        </p>

        <br />

        <h2 class="sub-title">Technologies Used for the Front End</h2>
        <p>I constructed the Front End of the MVP using the following:</p>
        <br />
        <v-row justify="space-around">
          <div>
            <v-icon color="#282828" size="100">mdi-react</v-icon>
            <h2>React JS</h2>
          </div>
          <div>
            <h1 color="#282828" class="express">EX</h1>
            <h2>Express JS</h2>
          </div>
          <div>
            <v-icon color="#282828" size="100">mdi-nodejs</v-icon>
            <h2>Node JS</h2>
          </div>
          <div>
            <v-icon color="#282828" size="100">mdi-language-html5</v-icon>
            <h2>HTML 5</h2>
          </div>
          <div>
            <v-icon color="#282828" size="100">mdi-language-css3</v-icon>
            <h2>CSS3</h2>
          </div>
        </v-row>
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
    <v-row align="start" justify="start">
      <!-- Design Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">High Fidelity Designs</h1>
        <br />
        <p>
          We presented our low-fidelity wireframes to the client, showcasing our
          design ideas and seeking their preferred direction. After agreeing on
          versions of the designs they liked and the functionality that could be
          implemented within a relatively short timeframe, we proceeded to
          create high-fidelity designs. These designs adhered to our visual
          guidelines to maintain a cohesive style. Subsequently, we developed an
          initial functional prototype to facilitate design testing.
        </p>
      </v-col>
    </v-row>
    <v-row justify="center" align="center" class="py-10">
      <!-- First Row -->
      <v-col cols="12" sm="6" md="5">
        <v-img
          :src="require('@/assets/interview_ai/landing_page_hifi.png')"
          alt="Sketch 1"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="6">
        <v-img
          :src="require('@/assets/interview_ai/position_information.png')"
          alt="Sketch 2"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="6">
        <v-img
          :src="require('@/assets/interview_ai/specific_topics.png')"
          alt="Sketch 3"
          class="sketch-image"
        ></v-img>
      </v-col>
      <!-- Second Row -->
      <v-col cols="12" sm="6" md="6">
        <v-img
          :src="require('@/assets/interview_ai/edit_questions.png')"
          alt="Sketch 4"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="6">
        <v-img
          :src="require('@/assets/interview_ai/dashboard_hifi.png')"
          alt="Sketch 5"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="6">
        <v-img
          :src="require('@/assets/interview_ai/past_interviews.png')"
          alt="Sketch 6"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="6">
        <v-img
          :src="require('@/assets/interview_ai/interview_summary.png')"
          alt="Sketch 6"
          class="sketch-image"
        ></v-img>
      </v-col>
    </v-row>
    <v-row align="start" justify="start">
      <!-- Testing Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Testing and Iteration</h1>
        <br />
        <p>
          We conducted 5 moderated usability tests with the high-fidelity
          prototype to determine if our designs effectively addressed the issues
          encountered in the existing live product. The participants included
          users working in human resources, hiring managers, and small business
          owners. All interviews were conducted and recorded through Zoom.
        </p>
        <h2 class="section-title">Data Synthesis and Insights</h2>
      </v-col>
      <ExpandableImage
        :imageSrc="require('@/assets/interview_ai/data_synthesis.png')"
      ></ExpandableImage>
      <h3 class="section-title">Findings</h3>
      <br />
      <br />
      <ul>
        <li>
          Users anticipated less manual input when completing forms,
          particularly since it is an AI platform.
        </li>
        <li>
          Users desired increased personalization and transparency regarding
          AI-generated questions.
        </li>
        <li>
          Users experienced confusion distinguishing between AI-generated
          questions and their own custom questions in the script editor.
        </li>
        <li>
          The current script editor saves interview scripts assigned
          specifically to a candidate rather than a role. This presents an issue
          as it is time-consuming to create non-reusable scripts. This
          constraint was imposed by the client due to their structured database.
        </li>
        <li>
          All users found the conduct interview page overwhelming due to
          information overload and multitasking. They did not find the AI
          follow-up question functionality useful. However, the client insisted
          on keeping this feature.
        </li>
        <li>
          Users expected the AI to listen and transcribe the interview to allow
          them to focus more on the candidate's answers. However, the client
          mentioned that this was not a currently feasible addition.
        </li>
        <li>
          Users desired more transparency regarding the breakdown of scores,
          especially in edge cases.
        </li>
      </ul>
      <br />
      <p>
        Based on the findings and some of the constraints mentioned above, we
        iterated on the designs. It is important to mention that we also had a
        tight timeline to deliver these designs. Therefore, we did not designed
        a mobile version of the product.
      </p>
    </v-row>
    <v-row justify="center" align="center" class="justify-center">
      <ExpandableImage
        :imageSrc="require('@/assets/interview_ai/candidate-info.png')"
      ></ExpandableImage>
      <ExpandableImage
        :imageSrc="require('@/assets/interview_ai/candidate-info-1.png')"
      ></ExpandableImage>
      <ExpandableImage
        :imageSrc="require('@/assets/interview_ai/candidate-info-2.png')"
      ></ExpandableImage>
      <ExpandableImage
        :imageSrc="require('@/assets/interview_ai/candidate-info-3.png')"
      ></ExpandableImage>
    </v-row>
    <h3 class="section-title">Prototype</h3>
    <br />
    <p>
      A functional prototype of the design was created in Figma as a deliverable
      to the client. Due to time limitations, this prototype was not tested.
    </p>
    <Button
      externalLink="https://www.figma.com/proto/gOCyIpkYDgRTBfklXqzF0G/InterviewAI_Share?page-id=266%3A3931&type=design&node-id=270-12030&scaling=min-zoom&starting-point-node-id=270%3A12030&t=UMhTIpgfFaaK2Irr-1"
      target="_blank"
      class="mt-2"
    >
      Live Prototype
    </Button>
    <br />
    <br />
    <h3 class="section-title">Recommendations for Future Improvements</h3>
    <br />
    <h4 class="section-title">General Recommendations</h4>
    <br />
    <ol>
      <li>
        Select a specific target audience to optimize visual design and
        effectiveness. Focus on segments like inexperienced interviewers, domain
        non-experts, or startups vs. enterprise for a tailored solution. This
        will effectively achieve desired outcomes, such as increased sign-up
        rates.
      </li>
      <li>
        Emphasize and express the mission of InterviewAI (e.g., fair interviews)
        to appeal to more users and increase sign-up rates. This will refine the
        designs and achieve desired outcomes effectively.
      </li>
      <li>
        Think about scalability and what needs to happen on both design and
        development front to be usable in the future when there is a large scale
        of users
      </li>
      <li>
        Incorporate a business model early on and set up metrics and analytics
        to have hard data and be aware of biased metrics (and why they are not
        reliable)
      </li>
      <li>
        During testing, we noticed users found the follow up question feature to
        be more confusing than useful. We have tried to solve this in our latest
        design, but it requires testing to validate.
      </li>
    </ol>
    <br />
    <h4 class="section-title">Short-Term Recommendations</h4>
    <br />
    <ol>
      <li>
        Users need to save their interview scripts by role/position. This will
        help users re-use the same script with other candidates (saves time) and
        helps with standardization (reduce bias in hiring decision).
      </li>
      <li>
        Users need the AI to generate questions and an evaluation rubric based
        on the resume to get tailored and personalized questions for the
        interview (helps save time).
      </li>
      <li>
        Users need to having recording and transcription of the interview so
        they can focus all their attention on the interview and ability to
        review at a later date.
      </li>
      <li>
        Users need more automation wherever possible to save time entering data
        manually.
      </li>
      <li>
        Users need the signup to happen at the beginning so the interview flow
        does not get interrupted (or risk turning away users) and/or signup at
        the end to allow users to see the full benefits of the product before
        committing to signup.
      </li>
      <li>
        Users expect the AI to do the tedious manual work to save them time and
        resources.
      </li>
    </ol>
    <br />
    <h4 class="section-title">Long-Term Recommendations</h4>
    <br />
    <ol>
      <li>
        Users need the AI to learn from their most commonly asked questions for
        a position so that they can get tailored recommendations that will help
        them improve the quality of their interview questions.
      </li>
      <li>
        Users need Interview AI to integrate with other ATS systems so that they
        can have a clear track record of the candidates that they interview.
      </li>
    </ol>
    <br />
    <br />
  </v-container>
</template>

<script>
import Stateless from '@/components/Stateless.vue'
import ExpandableImage from '@/components/ExpandableImage.vue'
import ImageGrid from '@/components/ImageGrid.vue'
import Button from '@/components/Button.vue'

export default {
  components: { ExpandableImage },
  data() {
    return {
      logos: [
        [
          {
            src:
              'https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg',
            alt: 'React',
          },
        ],
        [
          {
            src:
              'https://upload.wikimedia.org/wikipedia/commons/6/6a/Redux.svg',
            alt: 'Redux',
          },
        ],
        [
          {
            src:
              'https://upload.wikimedia.org/wikipedia/commons/9/9d/Node.js_logo.svg',
            alt: 'Node.js',
          },
        ],
        [
          {
            src:
              'https://upload.wikimedia.org/wikipedia/commons/6/6f/Socket.io_logo_2014.svg',
            alt: 'Socket.IO',
          },
        ],
        [
          {
            src:
              'https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png',
            alt: 'JavaScript',
          },
        ],
        [
          {
            src:
              'https://upload.wikimedia.org/wikipedia/commons/2/23/HTML5_logo_and_wordmark.svg',
            alt: 'HTML5',
          },
        ],
        [
          {
            src:
              'https://upload.wikimedia.org/wikipedia/commons/6/62/CSS3_logo.svg',
            alt: 'CSS',
          },
        ],
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

.express {
  font-size: 66px;
  font-weight: 100;
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
