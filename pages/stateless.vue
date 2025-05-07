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
    <v-row align="start" justify="start" class="color-background">
      <!-- Define Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Define</h1>
        <br />
        <p>
          After conducting primary and secondary research, I focused my
          attention on understanding the technical aspects of the backend and
          familiarizing with the API. This was an important step because the
          system had several constraints and needed the user to follow a
          particular flow because of peculiarities of the network functions
          orchestrator. After a few days, I created the following user flow.
        </p>

        <h2 class="sub-title">User Flow</h2>
        <br />
        <ExpandableImage
          :imageSrc="require('@/assets/stateless/user_flow.png')"
        ></ExpandableImage>
      </v-col>
    </v-row>
    <v-row align="start" justify="start">
      <!-- Design Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Design</h1>
        <br />
        <p>
          After identifying the user needs and agreeing with a user flow, I
          started creating the designs. I decided that my designs needed to
          cover the following:
        </p>
        <ul>
          <li>
            A way to start and stop network traffic.
          </li>
          <li>
            Functionality to add servers and network functions.
          </li>
          <li>
            Functionality to increase and decrease network traffic.
          </li>
          <li>
            Show the servers and the network functions on the UI
          </li>
          <li>
            A graph to show the changes in network traffic and how these
            affected the latency
          </li>
          <li>
            Logs to show what happens in the system
          </li>
        </ul>
        <br />

        <h2 class="sub-title">Sketches</h2>
        <br />
        <p>
          I created a series of sketches to put together the elements mentioned
          above and test my ideas. Due to the short time frame to design and
          develop the MVP, I carried out gorilla testing with my co-workers at
          the office. I was aware that this would lead to some bias, but I
          considered that it was important to get some quick feedback at this
          stage.
        </p>
      </v-col>
    </v-row>
    <v-row justify="center" align="center" class="py-10">
      <!-- First Row -->
      <v-col cols="12" sm="6" md="8">
        <v-img
          :src="require('@/assets/stateless/Stateless1.1.png')"
          alt="Sketch 1"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="8">
        <v-img
          :src="require('@/assets/stateless/Stateless1.2.png')"
          alt="Sketch 2"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="8">
        <v-img
          :src="require('@/assets/stateless/Stateless1.3.png')"
          alt="Sketch 3"
          class="sketch-image"
        ></v-img>
      </v-col>
      <!-- Second Row -->
      <v-col cols="12" sm="6" md="8">
        <v-img
          :src="require('@/assets/stateless/Stateless1.4.png')"
          alt="Sketch 4"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="8">
        <v-img
          :src="require('@/assets/stateless/Stateless1.5.png')"
          alt="Sketch 5"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="8">
        <v-img
          :src="require('@/assets/stateless/Stateless2.1.png')"
          alt="Sketch 6"
          class="sketch-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="8">
        <v-img
          :src="require('@/assets/stateless/Stateless3.1.png')"
          alt="Sketch 6"
          class="sketch-image"
        ></v-img>
      </v-col>
    </v-row>
    <v-row align="start" justify="start">
      <!-- Design Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">High Fidelity Prototypes</h1>
        <br />
        <p>
          Due to time constraints, I prioritized the creation of high-fidelity
          mockups over initial wireframes to ensure we had visually compelling
          materials for key events—such as Connect X—where Stateless was being
          showcased to investors and potential clients.
        </p>
        <p>
          The wireframes were subsequently developed based on user feedback
          gathered during the testing of these high-fidelity sketches. Key
          insights included:
        </p>
        <ol>
          <li>
            Simplifying interaction design by removing dual columns and the
            add/subtract buttons, which users found cumbersome and unintuitive.
          </li>
          <li>
            Increasing the size of the network topology layout to improve
            readability and user comprehension.
          </li>
          <li>
            Clarifying button labels and instructions to make actions more
            explicit and reduce user confusion.
          </li>
        </ol>
      </v-col>
    </v-row>
    <v-row justify="center" align="center" class="py-10">
      <!-- First Row -->
      <v-col cols="12" sm="6" md="8">
        <v-img
          :src="require('@/assets/stateless/stateless_mvp_intro.png')"
          alt="wireframe 1"
          class="wireframe-image"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="8">
        <v-img
          :src="require('@/assets/stateless/stateless_second_step.png')"
          alt="wireframe 2"
          class="wireframeimage"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" md="8">
        <v-img
          :src="require('@/assets/stateless/stateless_third_step.png')"
          alt="wireframe 3"
          class="wireframe-image"
        ></v-img>
      </v-col>
      <!-- Second Row -->
      <v-col cols="12" sm="6" md="8">
        <v-img
          :src="require('@/assets/stateless/stateless_mvp.png')"
          alt="wireframe 4"
          class="sketch-image"
          width="800"
        ></v-img>
      </v-col>
    </v-row>

    <v-row align="start" justify="start">
      <!-- Testing Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Testing and Iteration</h1>
        <br />
        <p>
          I conducted limited user testing primarily due to time constraints and
          the lack of technology and tools for creating a dynamic, interactive
          prototype for the MVP. Instead, I carried out informal guerrilla
          testing with my colleagues using high-definition mock-ups before
          proceeding to code the app.
        </p>
        <p>
          Once the first versions of the app were ready, I conducted user
          testing with five colleagues. However, since the app was already
          coded, making certain changes based on their feedback was challenging.
          For example, users consistently requested filters on the logs, but
          implementing this required major code changes. Due to time
          constraints, I focused on addressing the easier changes identified
          through user testing.
        </p>
        <p>
          This experience taught me the importance of having adequate time and
          resources for thorough user testing and the value of creating
          interactive prototypes before coding to allow for more flexibility in
          incorporating user feedback.
        </p>
      </v-col>

      <ExpandableImage
        :imageSrc="
          require('@/assets/stateless/stateless_feedback_wireframes.png')
        "
      ></ExpandableImage>
    </v-row>
    <h3 class="section-title">Prototype</h3>
    <br />
    <p>
      A functional prototype of the design was created in Figma.
    </p>
    <Button
      externalLink="https://www.figma.com/proto/M3SnM1ec87vCBcoUUROEL8/stateless-mvp-recreation?page-id=95%3A394&node-id=115-1174&viewport=1711%2C1292%2C0.25&t=OcgWNFJKVNhd9RD1-1&scaling=scale-down&content-scaling=fixed&starting-point-node-id=115%3A1174"
      class="mt-2"
      target="_blank"
      rel="noopener noreferrer"
    >
      Live Prototype
    </Button>
    <br />
    <br />
    <v-row align="start" justify="start">
      <!-- Project Overview Section -->
      <v-col cols="12" md="10">
        <h1 class="section-title">Takeaways and Improvements</h1>
        <br />
        <p>
          It’s important to note that the MVP of Stateless software was designed
          and built within a very short time frame and under numerous
          technological constraints. Despite these challenges and the potential
          for many improvements, I focused my efforts on the subsequent software
          development. However, the MVP successfully demonstrated the system’s
          functionality, securing 1.5 million USD in seed funding and 12.5
          million USD in Series A funding.
        </p>
        <p>
          This experience highlighted the difficulties of managing time
          effectively while designing and coding a product, particularly in
          allocating sufficient time for research. If I could revisit this
          project, I would approach it differently in several ways:
        </p>
        <ul>
          <li>
            Organized Research Plan: Establish and adhere to a well-structured
            research plan from the beginning.
          </li>
          <li>
            Stakeholder Communication: Clearly communicate the importance of
            conducting research and outline my plan to all stakeholders.
          </li>
          <li>
            Efficient Research Methodologies: Use faster research methodologies,
            such as Google Venture’s design sprint.
          </li>
          <li>
            Prototyping Over Coding: Invest more time in creating interactive
            prototypes in Figma before coding. At the time, the technology for
            interactive prototyping was insufficient, so I went straight to
            coding and tested the solution post-build. This approach was
            inefficient, as making design changes in code is significantly
            harder.
          </li>
        </ul>
        <p>
          This project was a valuable learning experience, emphasizing the
          importance of research, prototyping, and effective time management in
          UX design and development.
        </p>
        <br />
        <Button link="/interviewai" color="#3c9196" text-color="white">
          Go to next Project
        </Button>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import Stateless from '@/components/Stateless.vue'
import ExpandableImage from '@/components/ExpandableImage.vue'
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
