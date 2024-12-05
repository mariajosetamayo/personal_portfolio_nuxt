<template>
  <v-btn
    :to="link"
    :href="externalLink"
    class="custom-button"
    :large="large"
    :rounded="rounded"
    :elevation="elevation"
    v-bind="btnProps"
  >
    <slot>Default Text</slot>
  </v-btn>
</template>

<script>
export default {
  name: 'CustomButton',
  props: {
    link: {
      type: String,
      default: null, // Internal link (NuxtLink)
    },
    externalLink: {
      type: String,
      default: null, // External link (anchor tag)
    },
    large: {
      type: Boolean,
      default: true, // Large button
    },
    rounded: {
      type: Boolean,
      default: true, // Rounded corners
    },
    elevation: {
      type: [Number, String],
      default: 2, // Material design elevation
    },
    btnProps: {
      type: Object,
      default: () => ({}), // Additional v-btn props
    },
  },
}
</script>

<style scoped>
.custom-button {
  background-color: #3c9196 !important; /* Consistent button color */
  color: white !important; /* Ensure text is white */
  text-transform: uppercase; /* Optional: make text uppercase */
  font-weight: bold; /* Optional: bold text */
  border-radius: 8px; /* Optional: slightly rounded corners */
}

.custom-button:hover {
  background-color: #337c80 !important; /* Slightly darker on hover */
}
</style>
