<script setup lang="ts">

const props = defineProps({
  url: {
    type: String,
    default: null,
  }
})

const url = props.url
</script>

<template>
  <div class="item">
    <img :src=url :alt=url />
  </div>
</template>
