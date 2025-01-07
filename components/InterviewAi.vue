<template>
  <v-container fluid class="hero-section pa-0">
    <v-row class="align-center fill-height">
      <!-- Left Content: Text and Button -->
      <v-col cols="12" md="6" class="text-left">
        <v-img
          :src="require('@/assets/interview_ai_logo.png')"
          alt="InterviewAI Logo"
          max-height="80"
          contain
          class="mb-6"
        ></v-img>
        <v-img
          :src="require('@/assets/rectangle_shape_ia.png')"
          alt="InterviewAI Logo"
          max-height="80"
          contain
          class="mb-6"
        ></v-img>
        <div class="content">
          <p class="subtitle-1 mb-5">
            An AI-powered app that assists in conducting and creating
            interviews.
          </p>
          <Button
            link="/interviewai"
            color="#3c9196"
            text-color="white"
            v-if="showButton"
          >
            Go to Project
          </Button>
        </div>
      </v-col>

      <!-- Right Content: Laptop Image -->
      <v-col cols="12" md="6" class="text-center">
        <v-img
          :src="require('@/assets/interview_ai_screenshot.png')"
          alt="Hero Laptop Image"
          max-width="100%"
          class="hero-image"
        ></v-img>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import Button from '@/components/Button.vue'
export default {
  name: 'HeroSection',
  props: {
    showButton: {
      type: Boolean,
      default: true, // By default, the button is hidden
    },
  },
}
</script>

<style scoped>
.hero-section {
  background: linear-gradient(90deg, #e3f8ff 0%, #c3e2f8 100%);
  background-size: 100% 50%; /* Adjusts the size of the line */
  height: 70vh; /* Full height for hero section */
  padding: 2rem;
  padding-left: 50px;
  border-radius: 3px;
  margin-bottom: 50px;
}

.hero-image {
  object-fit: contain;
}

.content h1,
.content p,
.content .v-btn {
  margin-left: 50px; /* Align with logo */
}

@media (max-width: 960px) {
  .hero-section {
    text-align: center;
    padding: 1rem;
    margin-top: 5rem;
    height: 80vh;
  }

  .content h1,
  .content p,
  .content .v-btn {
    margin-left: 20px; /* Override to center on mobile */
  }
}
</style>
