<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8">
      <div class="flex-container">
        <div class="centered-content">
          <div>
            <h1 class="custom-title">Hi, I’m Maria Tamayo</h1>
          </div>
          <div class="typewriter-container">
            <h2 id="title-typed" class="custom-sub-title"></h2>
          </div>
          <div>
            <p>
              I use the power of tech to craft harmonious experiences for
              everyone.
            </p>
          </div>
        </div>
      </div>
    </v-col>
  </v-row>
</template>

<script>
import Typed from 'typed.js'
export default {
  name: 'IndexPage',
  mounted() {
    new Typed('#title-typed', {
      strings: ['Front-End Engineer', 'UX/UI Designer'],
      typeSpeed: 70,
      backSpeed: 25,
      backDelay: 1500,
      loop: true,
    })
  },
}
</script>
<style scoped>
.flex-container {
  display: flex;
  align-items: center; /* Center vertically */
  justify-content: center; /* Optional: Center horizontally */
  height: 70vh; /* Full viewport height */
}

.centered-content {
  padding: 20px;
}
.custom-title {
  font-size: 70px; /* Adjust as needed */
  font-weight: bold; /* Optional */
  font-family: Bitter;
}

.custom-sub-title {
  font-size: 40px; /* Adjust as needed */
  font-weight: medium; /* Optional */
  font-family: Bitter;
  color: #3a9198;
  padding-bottom: 20px;
}
.typewriter-container {
  height: 3rem; /* Match the height of the text */
  overflow: hidden; /* Prevent content shift */
  font-size: 1.5rem; /* Consistent font size */
  display: flex; /* Keeps alignment consistent */
  align-items: center; /* Vertically center text */
  font-family: Bitter; /* Optional: Typewriter-style font */
}
</style>
