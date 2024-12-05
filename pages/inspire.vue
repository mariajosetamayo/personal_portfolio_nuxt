<template>
  <v-row>
    <v-col class="text-center">
      <InterviewAi></InterviewAi>
      <FitnessTribe></FitnessTribe>
    </v-col>
  </v-row>
</template>

<script>
import FitnessTribe from '@/components/FitnessTribe.vue'
import InterviewAi from '@/components/InterviewAi.vue'
export default {
  name: 'InspirePage',
}
</script>
