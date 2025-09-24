<template>
  <div class="text-center p-6 rounded-lg transition-all duration-300 hover:shadow-lg hover:-translate-y-2" :class="cardClass">
    <div class="w-12 h-12 rounded-full flex items-center justify-center mx-auto mb-4 text-xl font-bold" :class="iconClass">
      {{ stepNumber }}
    </div>
    <h3 class="text-xl font-semibold mb-3">{{ title }}</h3>
    <p class="text-gray-600">{{ description }}</p>
  </div>
</template>

<script setup>
defineProps({
  stepNumber: {
    type: String,
    required: true
  },
  title: {
    type: String,
    required: true
  },
  description: {
    type: String,
    required: true
  },
  cardClass: {
    type: String,
    default: 'bg-blue-50'
  },
  iconClass: {
    type: String,
    default: 'bg-blue-600 text-white'
  }
})
</script>
