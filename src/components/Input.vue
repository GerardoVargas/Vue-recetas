<template>
   <v-container>
     <v-row>
       <v-col xs="12" lg="4"> 
         <v-text-field
            label="¿Qué se te antoja hoy?"
            outlined
            :value="value"
          >
          </v-text-field>
       </v-col>
     </v-row>
   </v-container>
</template>

<script>
export default {
  name: 'Input',
  props: {
    value: {
      type: String,
      required: true
    }
  }
}
</script>