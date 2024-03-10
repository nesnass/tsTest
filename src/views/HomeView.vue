<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
import { Draggable } from '@braks/revue-draggable'
</script>

<template>
  <main>
    <Draggable />
    <TheWelcome />
  </main>
</template>
