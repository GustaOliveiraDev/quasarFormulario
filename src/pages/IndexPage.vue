<template>
  <q-page>

    <p>Formulário Quasar</p>

    <q-input
     rounded outlined
     v-model="text"
    label="Digite seu Nome"
    
    />
    
  </q-page>
</template>





<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>
