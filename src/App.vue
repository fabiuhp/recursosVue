<template>
  <h1>{{ message }}</h1>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  data() {
    return {
      message: 'Hello'
    }
  },
  beforeCreate() {
    console.log('Antes da criação')
  },
  created() {
    console.log('Depois da criação')
  }
})
</script>
