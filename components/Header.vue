<script setup lang="ts">

const props = defineProps({
  title: {
    type: String,
    required: true
  },
  description: {
    type: String,
    default: null,
  }
})

const title = props.title
const description = props.description
</script>

<template>
  <div v-if="description" class="header">
    <div class="small_title">{{ title }}</div>
    <p class="description">{{ description }}</p>
  </div>
  <div v-else>
    <h1 class="big_title">{{ title }}</h1>
  </div>
</template>
