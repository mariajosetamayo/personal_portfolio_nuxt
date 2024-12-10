<template>
  <v-container fluid>
    <!-- Row with proper spacing between images -->
    <v-row dense align="center" justify="center" class="pa-4">
      <!-- Loop through images to create responsive grid items -->
      <v-col
        v-for="(image, index) in images"
        :key="index"
        cols="12"
        sm="6"
        md="4"
        lg="3"
        class="d-flex justify-center"
      >
        <!-- Image display -->
        <v-img
          :src="image.src"
          :alt="image.alt"
          max-height="500"
          max-width="300"
          contain
        />
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  props: {
    // Prop to pass an array of images
    images: {
      type: Array,
      default: () => [
        // { src: require('@/assets/screen1.png'), alt: 'Screen 1' },
        // { src: require('@/assets/screen2.png'), alt: 'Screen 2' },
        // { src: require('@/assets/screen3.png'), alt: 'Screen 3' },
        // { src: require('@/assets/screen4.png'), alt: 'Screen 4' },
        // { src: require('@/assets/screen5.png'), alt: 'Screen 5' },
        // { src: require('@/assets/screen6.png'), alt: 'Screen 6' },
        // { src: require('@/assets/screen7.png'), alt: 'Screen 7' },
        // { src: require('@/assets/screen8.png'), alt: 'Screen 8' },
        // { src: require('@/assets/screen9.png'), alt: 'Screen 9' },
        // { src: require('@/assets/screen10.png'), alt: 'Screen 10' }
      ],
    },
  },
}
</script>

<style scoped>
/* Optional styling for images */
.shadow {
  border-radius: 8px;
}

/* Ensure no overflow or overlap */
.v-img {
  overflow: hidden;
}
</style>
