<template>
  <v-row>
    <v-col class="text-center">
      <Stateless></Stateless>
      <InterviewAi></InterviewAi>
      <FitnessTribe></FitnessTribe>
    </v-col>
  </v-row>
</template>

<script>
import Stateless from '@/components/Stateless.vue'
import FitnessTribe from '@/components/FitnessTribe.vue'
import InterviewAi from '@/components/InterviewAi.vue'
import GalleryPal from '@/components/GalleryPal.vue'
import Diversify from '@/components/Diversify.vue'
export default {
  name: 'Work',
}
</script>
