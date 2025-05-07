<template>
  <v-container fluid class="experience-section py-10">
    <v-row justify="center">
      <v-col cols="12" md="8" class="text-center">
        <h1 class="text-h4 font-weight-bold text-center">My Hybrid Skills</h1>
        <p class="subtitle-1">
          Over the years, I have cultivated a unique blend of technical
          expertise and interpersonal skills to create innovative solutions and
          drive success.
        </p>
          <v-btn
            @click="downloadPDF"
            class="btn-download"
            color="#3c9196"
          >
            Resume
          </v-btn>
        </div>
      </v-col>
    </v-row>
    <v-row justify="center" class="mt-6">
      <!-- Skill 1 -->
      <v-col cols="12" sm="6" md="4" class="d-flex justify-center">
        <v-card class="pa-4 skill-card">
          <v-icon color="#3c9196" size="48">mdi-laptop-account</v-icon>
          <h3 class="font-weight-bold mt-4">UX/UI Design</h3>
          <p class="mt-2 text-center">
            I bring extensive experience across diverse projects, encompassing
            every stage of the UX/UI design process. Additionally, I also work
            in product design and branding, delivering cohesive and impactful
            solutions that align with user needs and business goals.
          </p>
        </v-card>
      </v-col>

      <!-- Skill 2 -->
      <v-col cols="12" sm="6" md="4" class="d-flex justify-center">
        <v-card class="pa-4 skill-card">
          <v-icon color="#3c9196" size="48">mdi-notebook-edit</v-icon>
          <h3 class="font-weight-bold mt-4">Research</h3>
          <p class="mt-2 text-center">
            I possess expertise in social science and public health research,
            with a focused specialization in behavior change strategies.
          </p>
        </v-card>
      </v-col>

      <!-- Skill 1 -->
      <v-col cols="12" sm="6" md="4" class="d-flex justify-center">
        <v-card class="pa-4 skill-card">
          <v-icon color="#3c9196" size="48">mdi-code-tags</v-icon>
          <h3 class="font-weight-bold mt-4">Technical Expertise</h3>
          <p class="mt-2 text-center">
            I have experience with React.js, Vue.js, Nuxt.js, Node.js, MongoDB,
            and SQL. Additionally, I am a Salesforce-certified administrator
            with hands-on expertise in developing components using the
            Salesforce Lightning Component Framework.
          </p>
        </v-card>
      </v-col>
    </v-row>
    <v-row justify="center" class="mt-6">
      <!-- Skill 1 -->
      <v-col cols="12" sm="6" md="4" class="d-flex justify-center">
        <v-card class="pa-4 skill-card">
          <v-icon color="#3c9196" size="48">mdi-palette-outline</v-icon>
          <h3 class="font-weight-bold mt-4">Visual Arts</h3>
          <p class="mt-2 text-center">
            I am proficient in academic drawing techniques, oil painting, and
            art history focused on the Renaissance.
          </p>
        </v-card>
      </v-col>

      <!-- Skill 2 -->
      <v-col cols="12" sm="6" md="4" class="d-flex justify-center">
        <v-card class="pa-4 skill-card">
          <v-icon color="#3c9196" size="48">mdi-account-group</v-icon>
          <h3 class="font-weight-bold mt-4">Entrepeneurship</h3>
          <p class="mt-2 text-center">
            I founded and served as CEO of Huitzi Solutions, a tech consulting
            company. Additionally, I completed two intensive programs on
            entrepreneurship.
          </p>
        </v-card>
      </v-col>

      <!-- Skill 3 -->
      <v-col cols="12" sm="6" md="4" class="d-flex justify-center">
        <v-card class="pa-4 skill-card">
          <v-icon color="#3c9196" size="48">mdi-crowd</v-icon>
          <h3 class="font-weight-bold mt-4">Leadership</h3>
          <p class="mt-2 text-center">
            I have led diverse teams throughout my career, from coordinating an
            international public health research collaboration to serving as the
            CEO of my own company.
          </p>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import Button from '@/components/Button.vue'
export default {
  name: 'ExperienceSection',
  methods: {
    downloadPDF() {
      const link = document.createElement('a')
      link.href = '/files/cv_mj_english.pdf'
      link.download = 'cv_mj_english.pdf'
      link.click()
    },
  },
}
</script>

<style scoped>
.title {
  font-family: Bitter;
}
.experience-section {
  background-color: #f7f9fc;
  margin-bottom: 50px;
  border-radius: 3px;
}

.skill-card {
  max-width: 300px;
  text-align: center;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

.skill-card h3 {
  color: #3c9196;
}

.skill-card p {
  color: #444;
}

.btn-download {
  color: #fff;
  font-weight: bold;
}

@media (max-width: 960px) {
  .experience-section {
    padding: 2rem 1rem;
    margin-top: 50px;
  }
}
</style>
