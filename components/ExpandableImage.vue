<template>
  <v-container>
    <!-- Image Thumbnail -->
    <v-img
      :src="imageSrc"
      alt="Expandable Image"
      class="my-4 image"
      max-width="900"
      @click="openDialog"
    />

    <!-- Dialog to display the full-size image -->
    <v-dialog v-model="dialog" max-width="100%">
      <v-card>
        <v-card-title class="text-h5"></v-card-title>
        <v-card-text>
          <v-img :src="imageSrc" alt="Full-size Image" />
        </v-card-text>
        <v-card-actions>
          <v-btn text @click="closeDialog">Close</v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
  </v-container>
</template>

<script>
export default {
  props: {
    imageSrc: {
      type: String,
      required: true,
    },
  },
  data() {
    return {
      dialog: false, // Controls the dialog visibility
    }
  },
  methods: {
    openDialog() {
      this.dialog = true // Open the dialog
    },
    closeDialog() {
      this.dialog = false // Close the dialog
    },
  },
}
</script>

<style scoped>
/* Add custom styles here */
</style>
