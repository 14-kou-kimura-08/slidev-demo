<script setup lang="ts">

const props = defineProps({
  text: {
    type: String,
    default: null,
  },
  from: {
    type: String,
    required: true,
  }
})

const text = props.text
</script>

<template>
  <div class="speech">
    <img class="speech_icon" :class="{ 'hidden_icon': from === 'wanko' }" src="hitsuji.png" >
    <div class="speech_bubble">
      {{ text }}
    </div>
    <img class="speech_icon" :class="{ 'hidden_icon': from === 'hitsuji' }" src="wanko.png">
  </div>
</template>
