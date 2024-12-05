<template>
  <v-container fluid class="hero-section">
    <!-- Top-right Decorative Image -->
    <v-img
      :src="require('@/assets/shape_ft_2.png')"
      alt="Top Right Decoration"
      class="corner-image top-right"
    ></v-img>
    <v-row align="center" justify="space-between" class="hero-row">
      <!-- Left Section: Logo and Text -->
      <v-col cols="12" md="6" class="text-section">
        <div class="logo">
          <v-img
            :src="require('@/assets/fitness_tribe_logo.png')"
            alt="Fitness Tribe Logo"
            max-width="120"
          ></v-img>
        </div>
        <h1 class="hero-title">
          Fitness
          <span class="highlight">Tribe</span>
        </h1>
        <p class="hero-subtitle">
          An app to get fit by sharing fitness goals and challenges with your
          friends.
        </p>
        <Button link="/" color="#3c9196" text-color="white">
          Go to Project
        </Button>
      </v-col>

      <!-- Right Section: App Screenshots -->
      <v-col cols="12" md="6" class="image-section">
        <div class="app-screens">
          <v-img
            :src="require('@/assets/fitnessTribePhone.png')"
            alt="Fitness App Screenshot 1"
            max-width="600"
            class="screenshot screenshot-main"
          ></v-img>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import Button from '@/components/Button.vue'
export default {
  name: 'FitnessHeroSection',
}
</script>

<style scoped>
.hero-section {
  background-color: #0b1624; /* Dark background */
  color: white;
  min-height: 70vh; /* Full screen height */
  display: flex;
  align-items: center; /* Center vertically */
  padding: 20px;
  position: relative; /* For absolute positioning of corner images */
  padding-left: 50px;
  border-radius: 3px;
  overflow: hidden;
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

.hero-subtitle {
  font-size: 1.25rem;
  margin-top: 1rem;
}

.image-section {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}

.app-screens {
  position: relative;
}

.screenshot {
  transition: transform 0.3s;
}

.screenshot-main {
  transform: rotate(-5deg); /* Tilt the main image */
}

/* Corner Images */
.corner-image {
  position: absolute;
  z-index: 1; /* Place behind content */
  opacity: 0.8; /* Slight transparency */
}

.top-right {
  top: 0;
  right: 0;
  width: 300px; /* Adjust size */
}

/* Responsive Styles */
@media (max-width: 768px) {
  .hero-section {
    flex-direction: column; /* Stack content vertically on mobile */
    text-align: center;
    margin-top: 5rem;
    padding: 10px;
    padding-top: 20px;
  }

  .hero-title {
    font-size: 2rem;
  }

  .hero-subtitle {
    font-size: 1rem;
  }

  .text-section {
    margin-bottom: 20px; /* Add spacing between text and images */
  }

  .image-section {
    justify-content: center;
  }

  .screenshot-main,
  .screenshot-secondary {
    transform: none;
    position: relative;
    top: 0;
    right: 0;
    max-width: 200px; /* Smaller images on mobile */
  }

  .corner-image {
    width: 100px; /* Smaller corner images on mobile */
    visibility: hidden;
  }
}
</style>
