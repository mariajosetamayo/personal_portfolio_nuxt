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
        <v-row justify="space-between" align="center" no-gutters>
          <v-col cols="12" sm="4" md="2" class="text-center">
            <v-icon color="#282828" size="100">mdi-react</v-icon>
            <h2>React JS</h2>
          </v-col>
          <v-col cols="12" sm="4" md="2" class="text-center">
            <h1 color="#282828" class="express">EX</h1>
            <h2>Express JS</h2>
          </v-col>
          <v-col cols="12" sm="4" md="2" class="text-center">
            <v-icon color="#282828" size="100">mdi-nodejs</v-icon>
            <h2>Node JS</h2>
          </v-col>
          <v-col cols="12" sm="4" md="2" class="text-center">
            <v-icon color="#282828" size="100">mdi-language-html5</v-icon>
            <h2>HTML 5</h2>
          </v-col>
          <v-col cols="12" sm="4" md="2" class="text-center">
            <v-icon color="#282828" size="100">mdi-language-css3</v-icon>
            <h2>CSS3</h2>
          </v-col>
        </v-row>
      </v-col>
    </v-row>

    <!-- Research Section -->
    <v-row class="py-10">
      <v-col cols="12">
        <h1>Research</h1>
      </v-col>
      <v-col cols="12" md="10">
        <h2 class="sub-title">Secondary Research</h2>
        <p>
          As a first step, I spent a significant amount of time understanding
          networks more in depth. After this period of learning, I started doing
          research about industry trends and what aspects would be appealing to
          investors in the MVP. These are some insights of my research.
        </p>
        <p>
          In 2017, the evolution of network function state decoupling products,
          particularly within Software-Defined Networking (SDN) and Network
          Function Virtualization (NFV), reflected several significant trends:
        </p>
        <ul>
          <li>
            Focus on Automation and Orchestration: Reports from Gartner
            highlighted a growing emphasis on automation and orchestration
            capabilities within SDN and NFV solutions. Vendors aimed to simplify
            network management through centralized controllers capable of
            automating provisioning and configuration tasks.
          </li>
          <li>
            Application-Centric Approaches: Research published in IEEE Network
            highlighted a shift towards application-centric approaches in
            network management. SDN and NFV solutions were increasingly tailored
            to align network policies and configurations with specific
            application requirements, optimizing performance and user
            experience.
          </li>
          <li>
            Analytics and Insights: There was a growing integration of analytics
            and insights capabilities into SDN and NFV platforms. Solutions
            offered real-time monitoring, predictive analytics, and actionable
            insights to optimize network performance and resource utilization
            (Source: Network World).
          </li>
        </ul>
      </v-col>
      <!-- Define Section -->
      <v-col cols="12" md="10">
        <h2 class="section-title">Competitor Analysis</h2>
        <br />
        <v-col cols="12" md="12">
          <h2 class="sub-title">Cisco Meraki</h2>
          <p>
            Cisco Meraki provides cloud-managed IT solutions for networking,
            security, and device management, simplifying administration and
            enhancing scalability for organizations through a centralized
            web-based dashboard.
          </p>
        </v-col>
        <v-row align="center" justify="space-around">
          <!-- Image Column -->
          <v-col cols="12" md="6">
            <v-img
              :src="require('@/assets/stateless/cisco_meraki.png')"
              alt="Research"
              contain
              max-height="600"
            ></v-img>
          </v-col>

          <!-- Card Column -->
          <v-col cols="12" md="6">
            <v-card class="dark-card-app">
              <v-card-title class="white--text">
                <h3 class="highlight">Likes</h3>
              </v-card-title>
              <v-card-text class="white--text">
                <ul>
                  <li>Visuals of analytics and system status.</li>
                  <li>
                    Provides options to filter the data displayed.
                  </li>
                  <li>The sidebar navigation is clear and easily accesible.</li>
                </ul>
              </v-card-text>
              <v-card-title class="white--text">
                <h3 class="highlight">Dislikes</h3>
              </v-card-title>
              <v-card-text class="white--text">
                <ul>
                  <li>
                    There is some information overload by showing too much data
                    at once. For instance, The table is displays too many rows.
                  </li>
                  <li>
                    White space is limited and has poor visual hierarchy, which
                    makes the dashboard hard to read.
                  </li>
                  <li>
                    The information architecture is confusing, especially in
                    places inside the dashboard that take the user to other
                    pages.
                  </li>
                </ul>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
        <br />
        <v-col cols="12" md="12">
          <h2 class="sub-title">Juniper Contrail</h2>
          <p>
            Juniper Contrail is an SDN solution focused on cloud-scale
            networking, providing virtualization and automation capabilities.
          </p>
        </v-col>
        <v-row align="center" justify="space-around">
          <!-- Image Column -->
          <v-col cols="12" md="6">
            <v-img
              :src="require('@/assets/stateless/juniper.png')"
              alt="Research"
              contain
              max-height="600"
            ></v-img>
          </v-col>

          <!-- Card Column -->
          <v-col cols="12" md="6">
            <v-card class="dark-card-app">
              <v-card-title class="white--text">
                <h3 class="highlight">Likes</h3>
              </v-card-title>
              <v-card-text class="white--text">
                <ul>
                  <li>
                    Has attractive and easy to read visuals of analytics and
                    system status.
                  </li>
                  <li>
                    UI has good use of visual hierarchy.
                  </li>
                  <li>The sidebar navigation is clear and easily accesible.</li>
                </ul>
              </v-card-text>
              <v-card-title class="white--text">
                <h3 class="highlight">Dislikes</h3>
              </v-card-title>
              <v-card-text class="white--text">
                <ul>
                  <li>
                    The colors used in the graphs and in some titles are too
                    light and make it hard to read the data.
                  </li>
                  <li>
                    There are a lot of cards with little information that could
                    be condensed into a table or another component to reduce
                    cognitive overload.
                  </li>
                  <li>
                    The ability to customize the UI to fit specific workflows or
                    preferences can be limited. pages.
                  </li>
                </ul>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
        <br />
        <v-col cols="12" md="12">
          <h2 class="sub-title">Palo Alto Networks</h2>
          <p>
            Palo Alto Networks is a global cybersecurity company that provides a
            wide range of products and services aimed at protecting
            organizations from cyber threats.
          </p>
        </v-col>
        <v-row align="center" justify="space-around">
          <!-- Image Column -->
          <v-col cols="12" md="6">
            <v-img
              :src="require('@/assets/stateless/palo_alto_networks.png')"
              alt="Research"
              contain
              max-height="600"
            ></v-img>
          </v-col>

          <!-- Card Column -->
          <v-col cols="12" md="6">
            <v-card class="dark-card-app">
              <v-card-title class="white--text">
                <h3 class="highlight">Likes</h3>
              </v-card-title>
              <v-card-text class="white--text">
                <ul>
                  <li>
                    Provides useful information about the network.
                  </li>
                  <li>
                    Uses tabs for easy access to some sections.
                  </li>
                  <li>Has filters and quick actions.</li>
                </ul>
              </v-card-text>
              <v-card-title class="white--text">
                <h3 class="highlight">Dislikes</h3>
              </v-card-title>
              <v-card-text class="white--text">
                <ul>
                  <li>
                    The UI looks outdated, resembling the style of software from
                    the 1990’s.
                  </li>
                  <li>
                    The navigation is somewhat confusing since there is a system
                    of tabs and a sidebar with many options that are not
                    organized in the most intuitive way.
                  </li>
                  <li>
                    The information architecture is confusing, especially
                    different styles of navigation (tabs and a sidebar) and
                    having two tabs menus.
                  </li>
                </ul>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
        <br />
        <br />
        <h2>Primary Research</h2>
        <p>
          My primary research involved interviews with five potential users,
          including network engineers and investors. Some interviews were
          conducted online via Google Meet, while others were in-person with an
          intern assisting in note-taking. The collected data was analyzed to
          identify patterns and categorized into various insights:
        </p>
        <ul>
          <li>
            Users prefer using a terminal for network configuration and
            management.
          </li>
          <li>
            Some users favor using a keyboard over a mouse for interface
            interaction.
          </li>
          <li>
            Users found graphical network status displays useful.
          </li>
          <li>
            Overall, opinions on current network configuration UIs were
            negative. Users reported wasting time learning poorly designed UIs.
          </li>
        </ul>
        <br />
        <p>Specific user frustrations included:</p>
        <ul>
          <li>
            Lack of control for certain tasks, with engineers preferring code
            over confusing flows.
          </li>
          <li>
            Vague or confusing language avoiding technical terms.
          </li>
          <li>
            Lack of trust due to insufficient system feedback, such as error
            handling and success notifications.
          </li>
          <li>
            Inconsistencies in the UI, such as displaying different sets of
            information on different pages.
          </li>
        </ul>
        <br />
        <br />
        <!-- Persona 1 -->
        <v-row>
          <!-- Left Column (Image and Description) -->
          <v-col cols="12" md="4" class="text-center persona-column">
            <!-- Circular Image -->
            <v-avatar size="200">
              <v-img
                alt="Network Engineer"
                :src="require('@/assets/stateless/network_engineer_avatar.png')"
              />
            </v-avatar>
            <br />
            <br />

            <!-- User Details -->
            <div class="mt-4">
              <h3 class="text-left">
                <strong>Age:</strong>
                30 years old
              </h3>
              <h3 class="text-left">
                <strong>Location:</strong>
                Denver, Colorado
              </h3>
              <br />
              <blockquote class="mt-3 text-left">
                “As a network engineer, I find that many network configuration
                UIs are often cluttered and counterintuitive. Poor design can
                lead to inefficiency and increased risk of errors, making it
                difficult to quickly identify and resolve issues. I prefer using
                the terminal.”
              </blockquote>
            </div>
          </v-col>

          <!-- Right Column (Title and Sections) -->
          <v-col cols="12" md="8">
            <!-- Title -->
            <h4>NETWORK ENGINEER WORKING IN A DATA CENTER</h4>
            <h2 class="mb-4 font-weight-bold">
              Calvin: The Detail-Oriented Network Engineer
            </h2>

            <!-- Sections -->
            <v-row>
              <!-- Behavior Section -->
              <v-col cols="12" class="mb-4">
                <h3 class="font-weight-bold">Behavior</h3>
                <div class="text-body-1">
                  <!-- Placeholder text; replace with actual content -->
                  Calvin works at a data center in Denver and is responsible for
                  making sure that the network infrastructure runs smoothly and
                  efficiently. He is very passionate about the latest trends in
                  technology and is very detailed oriented. He loves working
                  with dark themes in his user interfaces and is not bothered at
                  all by the terminal. He has great technical communication and
                  is very knowledgeable about his job.
                </div>
              </v-col>
              <!-- Frustrations Section -->
              <v-col cols="12" class="mb-4">
                <h3 class="font-weight-bold">Frustrations</h3>
                <ul>
                  <li>
                    Impact on Performance: State inconsistencies can impact
                    network performance by causing delays, packet loss, or
                    inefficient routing. Calvin needs to constantly monitor and
                    optimize network states to ensure optimal performance and
                    minimize latency.
                  </li>
                  <li>
                    Operational Overhead: Managing and maintaining consistent
                    network states require significant operational overhead.
                    Calvin must implement rigorous change management processes,
                    conduct regular audits, and invest in automation tools to
                    streamline state management tasks.
                  </li>
                  <li>
                    Security Risks: Inconsistent state management can pose
                    security risks by leaving vulnerabilities open.
                    Misconfigurations or outdated state information may create
                    loopholes that attackers could exploit to gain unauthorized
                    access or disrupt network operations.
                  </li>
                </ul>
              </v-col>
              <!-- User Needs Section -->
              <v-col cols="12">
                <h3 class="font-weight-bold">User Needs</h3>
                <ul>
                  <li>
                    Increase the performance of the network infrastructure so
                    that he can provide a better service to his clients.
                  </li>
                  <li>
                    Automation tools that can help him streamline state
                    management tasks so that he can reduce operational overhead.
                  </li>
                  <li>
                    A service that assists with the security of network
                    functions so that he can focus on other important aspects of
                    the network infrastructure.
                  </li>
                </ul>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
        <!-- Persona 2 -->
        <br />
        <br />
        <br />
        <v-row>
          <!-- Left Column (Image and Description) -->
          <v-col cols="12" md="4" class="text-center persona-column">
            <!-- Circular Image -->
            <v-avatar size="200">
              <v-img
                alt="Network Engineer"
                :src="require('@/assets/stateless/investor_avatar.png')"
              />
            </v-avatar>
            <br />
            <br />

            <!-- User Details -->
            <div class="mt-4">
              <h3 class="text-left">
                <strong>Age:</strong>
                50 years old
              </h3>
              <h3 class="text-left">
                <strong>Location:</strong>
                San Jose, California
              </h3>
              <br />
              <blockquote class="mt-3 text-left">
                “Today's network management software isn't just about
                efficiency; it's about transforming how we connect and
                communicate. I'm looking to invest in solutions that redefine
                scalability, security, and user experience in this rapidly
                evolving landscape.”
              </blockquote>
            </div>
          </v-col>

          <!-- Right Column (Title and Sections) -->
          <v-col cols="12" md="8">
            <!-- Title -->
            <h4>TECH VENTURE INVESTOR</h4>
            <h2 class="mb-4 font-weight-bold">
              Eddie: The Innovator Investor with Tech-Savvy Flair
            </h2>

            <!-- Sections -->
            <v-row>
              <!-- Behavior Section -->
              <v-col cols="12" class="mb-4">
                <h3 class="font-weight-bold">Behavior</h3>
                <div class="text-body-1">
                  Eddie, has a portfolio of diverse investments in a few Silicon
                  Valley startups. He brings sharp market insight, rigorous due
                  diligence, and strategic guidance to startups. He prioritizes
                  scalability, security, and market adoption, adapting swiftly
                  to tech trends while nurturing long-term growth opportunities.
                </div>
              </v-col>
              <!-- Frustrations Section -->
              <v-col cols="12" class="mb-4">
                <h3 class="font-weight-bold">Frustrations</h3>
                <p>
                  Eddie is frustrated by lack of innovation, poor market fit,
                  slow adoption, scalability issues, resistance to change, and
                  regulatory hurdles in startups he considers investing in.
                  These factors hinder growth and market impact, driving him to
                  seek tech ventures that can navigate these challenges
                  effectively.
                </p>
              </v-col>
              <!-- User Needs Section -->
              <v-col cols="12">
                <h3 class="font-weight-bold">User Needs</h3>
                <ul>
                  <li>
                    Eddie seeks startups that offer innovative technologies
                    capable of disrupting traditional network management
                    practices.
                  </li>
                  <li>
                    He values startups that clearly understand and address
                    market needs, ensuring their solutions provide tangible
                    benefits to customers.
                  </li>
                  <li>
                    Eddie seeks investments with strong potential for return on
                    investment (ROI), focusing on technologies poised for
                    sustainable growth and profitability.
                  </li>
                </ul>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
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

.persona-column {
  background-color: #ebedf2;
  padding-top: 30px;
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
