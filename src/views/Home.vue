<template>
  <div class="home">
    <h1>{{title}}</h1>
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const title = ref('TODOS')
</script>
