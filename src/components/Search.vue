<template>
  <v-container>
    <v-row>
      <v-col
        class="my-4"
        cols="12"
      >
      <Input :value="TESTEO" />
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import { Input } from './index'

export default {
  name: 'Search',
  components: {
    Input
  },
  data(){
    return {
      
    }
  }
}
</script>
