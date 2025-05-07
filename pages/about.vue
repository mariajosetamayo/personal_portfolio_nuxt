<template>
  <v-container fluid class="about-me-section">
    <!-- About Me Section -->
    <v-row align="center" justify="center" class="mb-10">
      <!-- Image Section -->
      <v-col cols="12" md="4" class="d-flex justify-center">
        <v-img
          :src="require('@/assets/mj_profile.png')"
          alt="Maria Tamayo"
          class="rounded"
          contain
        ></v-img>
      </v-col>

      <!-- Text Section -->
      <v-col cols="12" md="6">
        <h1 class="mb-4">My name is Maria Tamayo</h1>
        <p>
          I am a multidisciplinary professional passionate about bridging the
          gap between technology and human behavior. My journey has been shaped
          by a desire to challenge the status quo, which has led me to explore
          diverse avenues of knowledge and creativity. A significant focus of my
          work is understanding human behavior, a curiosity that inspired me to
          study psychology extensively. By integrating these insights with my
          technical expertise, I specialize in creating impactful digital
          products that influence behavior through thoughtful UX/UI design.
        </p>
        <p>
          Beyond my professional pursuits, I thrive on continuous learning and
          personal growth. My interests span a wide array of activities, from
          practicing Zen and Japanese calligraphy to engaging in outdoor
          adventures like rock climbing, mountaineering, and skiing. I also find
          joy in creative outlets such as playing the piano, drawing,
          photography, cooking, and exploring the world through travel.
        </p>
      </v-col>
    </v-row>

    <!-- Contact Me Section -->
    <v-row align="center" justify="center" class="contact-me-section">
      <v-col cols="12" md="10" class="text-center">
        <h2 class="font-weight-bold mb-4">Contact Me</h2>
        <p class="text-subtitle-1 mb-6">
          I'd love to hear from you! Feel free to reach out for project
          collaborations, opportunities, or even just to say hello.
        </p>
        <h4>Email: mariajose.tamayo@gmail.com</h4>
        <h4>LinkedIn: www.linkedin.com/in/mariajtamayo</h4>
        <h4>Instagram: @mjtmayo</h4>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'AboutMe',
}
</script>

<style scoped>
.about-me-section {
  background-color: #f9fafb;
  padding: 40px 20px;
}

h1 {
  font-weight: bold;
}

h2 {
  color: #3c9196;
}

.contact-me-section {
  background-color: #f0f4f8;
  padding: 40px 20px;
  border-radius: 8px;
}

.rounded {
  border-radius: 8px;
  max-height: 400px;
  max-width: 100%;
}

p {
  line-height: 1.6;
  font-size: 16px;
  color: #4a4a4a;
}

.v-btn {
  background-color: #3c9196 !important;
  color: white !important;
}
</style>
